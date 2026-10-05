# forkful-demo

A clickable food-ordering prototype with a placeholder brand ("Forkful") and made-up stores.

- Live app: https://beauagrawal01.github.io/forkful-demo/ (add to Home Screen for full-screen)
- `index.html` is the whole app. `brand-data.json` is the default brand data and messages that ship with it (regenerated on every update).

## Your settings survive updates

Brand, names, colors, the starting conversation, quick replies, courier replies, stores and menus, photos and the app icon are saved on your device (browser storage plus an IndexedDB copy). Updating the app never overwrites them: edited stores are kept, only untouched built-in ones get new content. Before a new version first runs, the previous settings are backed up on the device (Customize > Restore settings from before the last update).

A Home Screen app on iPhone starts with its own empty storage, so brand data and messages are carried in the link you add it from (`?cfg=`). Open Customize > Copy my install link, open that link in Safari, then Share > Add to Home Screen. The Home Screen name follows your brand name. Menus and photos carry over with Copy my settings.

Settings are per web address. To move them to another copy of the app, use Customize > Copy my settings, then paste into Apply pasted settings on the other copy.
