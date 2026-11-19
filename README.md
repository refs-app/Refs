# Refs

Save design references from any website (Instagram, YouTube, Pinterest, Behance, Dribbble, TikTok, X, Vimeo…) in one click from your browser, and organise them into collections in a desktop app.

- Everything is kept **on your computer**: no accounts, no cloud.
- Works on **Windows 10 and 11** with Chromium-based browsers: **Brave, Chrome, Edge, Opera, Arc**.
- It never downloads videos: it keeps the link and a thumbnail. YouTube and Vimeo videos play when you hover over them.

## Privacy

Refs has no servers, accounts or usage statistics. What you save (links, notes and thumbnails) stays in a folder on your computer and is not sent anywhere. The extension only reads the page you are saving, when you ask it to. YouTube and Vimeo previews play from those sites, like any embedded video. To tell you about new versions, the app checks this GitHub page when it opens and once a day, without sending anything about you; you can turn this off in **Settings**.

## Install Refs

There are two parts: the **app** and the browser **extension**. Both are downloaded from the [Releases](../../releases/latest) page.

### 1. The app

1. In [Releases](../../releases/latest), download **`Refs_…_x64-setup.exe`**.
2. Open it. As the app has no digital signature, Windows may show a blue warning ("Windows protected your PC"). Click **More info** and then **Run anyway**.
3. Follow the installer. It does not ask for administrator rights.
4. Open **Refs** from the Start menu. It has to be opened at least once for the extension to find it.

### 2. The extension

1. In [Releases](../../releases/latest), download **`Refs-extension-….zip`**.
2. Unzip it into a folder you will keep, for example `Documents\Refs-extension`. The browser loads it from there every time it starts.
3. In the browser's address bar, type:
   - Brave: `brave://extensions`
   - Chrome: `chrome://extensions`
   - Edge: `edge://extensions`
4. Turn on **Developer mode** (top right; in Edge it is on the left).
5. Click **Load unpacked** and choose the folder from step 2: the one that contains `manifest.json`.
6. Pin the extension: click the puzzle icon in the browser's toolbar, then the pin next to **Refs**.

### Check that it works

1. Open any post, for example on Instagram or Behance.
2. Click the Refs icon in the browser's toolbar. At the top of the popup you should see a green dot and "Connected to Refs".
3. Click **Save**. The reference appears in the app, in **Review**.

You can also right-click a page, a link or an image and choose **Save to Refs**.

If the popup says it cannot find the app, open Refs, go to **Settings** and click **Repair connection**.

## Using Refs

- **Review:** everything you save lands here until you put it in a collection.
- **Collections:** drag a reference onto a collection, or select it and press `M`. Each collection has a name, a description and a folder colour.
- **Pinned:** pin the collections you use most to the sidebar. **New Folder** creates a pinned collection.
- **Filter by platform:** the menu at the top right shows only the platforms you have saved from, with how many references each one has.
- **Shortcuts:** `M` move to a collection · `R` mark as reviewed · `Delete` move to the trash · double click to open the original.
- **Settings:** theme (light, dark or the Windows one), start with Windows, the trash, the folder where your references are, and checking for updates.

## Updating

When there is a new version, Refs tells you with a notice at the top of the window. Click **Download**, get the new installer and open it: it replaces the previous version and keeps your references. You can also check in **Settings → Check for updates**.

If the new version also brings a new extension (its page in [Releases](../../releases/latest) says so), unzip it into the same folder, replacing the files, and click the reload button of Refs on the browser's extensions page.

## Uninstalling

Go to **Windows Settings → Apps → Installed apps → Refs → Uninstall**. The uninstaller offers a box to delete the app's data: **if you tick it, all your references are deleted too**. If you leave it unticked, they stay in `%APPDATA%\com.refs.desktop`.

Remove the extension from the browser's extensions page.

## License

Refs is free for personal use. The code and design belong to the author: they may not be copied, modified or redistributed without permission. It is provided as is, without warranty. Details in [`LICENSE`](LICENSE).
