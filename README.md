# lyboai-releases

Public downloads for LyboAI. Source lives in private repositories; this
repository only holds release builds.

| Release tag | What | Assets |
|---|---|---|
| `v<version>` | LyboAI Edge Runtime CLI (`lybo`), the core of LYBO OS | `lybo.exe` (Windows x64), `lybo-linux-x64` |
| `studio-v<version>` | **LYBO Studio**, the desktop editor for local models, on-device agents and LYBO OS apps | Windows setup `.exe` and zip, macOS `.zip` (Apple silicon and Intel), Linux `.tar.gz` and `.deb`, the `.vsix` extension, `SHA256SUMS.txt` |
| `shell-v<version>` | **LYBO Edge Shell**, the starter app with demo mini apps (Expo, Android and iOS) | `lybo-edge-shell-<version>.zip` and `.sha256` |

`studio/latest.json` tells LYBO Studio which version is current on each
update channel (`stable`, `preview`). The LYBO Studio release workflow updates it.

LYBO Studio downloads from here: it installs the `lybo` runtime from the newest
`v*` release with a binary for the computer, and **New App → LYBO Edge Shell**
uses the newest `shell-v*` release.

## Licence

The LyboAI Edge Runtime, LYBO Studio and the LYBO Edge Shell are licensed under
the LYBO OS Commercial Licence: free for evaluation and development, a paid
production licence to ship. See https://lyboai.app/legal. LYBO Studio's
desktop app is built from Code - OSS (MIT).

## Notebooks

`notebooks/lyboai_quickstart.ipynb`: the Colab quickstart.
