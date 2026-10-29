# DevPurge downloads

Builds of **DevPurge for Mac**, the developer-cache cleaner.

- Website: https://404kidwiz.github.io/devpurge/
- Source, issues and safety guarantees: https://github.com/404kidwiz/devpurge

Grab the newest `.dmg` from [Releases](https://github.com/404kidwiz/devpurge-releases/releases/latest).
Verify it with `shasum -a 256 -c SHA256SUMS.txt`.

Requires macOS 14 or later. Unlimited scans and 3 cleanups free; $19 one-time license for up to 2 Macs.

## First launch

These builds are not yet notarized by Apple, so macOS blocks the first launch.
After dragging DevPurge to Applications:

1. Open DevPurge once. macOS says it can't verify the developer. Click **Done**.
2. Open **System Settings → Privacy & Security**, scroll down, click **Open Anyway** next to DevPurge.
3. Confirm with your password. Later launches open normally.

Check the download first: `shasum -a 256 -c SHA256SUMS.txt`.
