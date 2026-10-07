# Filter Everything — releases

This repository holds the released builds of Filter Everything and nothing else: installers, update files, and two small files the app reads to learn whether a newer version exists.

* `preview.json` — the newest release on the **Preview** track, which testers follow.
* `stable.json` — the newest release on the **Stable** track, which everyone else follows.

The installers are attached to each version's release on this repository's Releases page. Filter Everything runs on Apple Silicon Macs. The app's source code is not here.

When the app checks for an update it downloads one of those two files. The request says which version of the app is asking; it carries nothing about the person using it.
