# Grimfold Live

Browser playtest build of Grimfold, exported with Godot 4.7.2.

## Play

https://kohmir.github.io/Grimfold-Live/

Open in a recent browser with WebGL 2 support. On iPhone Safari, landscape is recommended. The build uses single-threaded WebAssembly and includes mobile textures; real iPhone compatibility has not yet been verified.

## Hosting

In **Settings → Pages**, choose **Deploy from a branch**, **main**, **/ (root)**, then Save. `.nojekyll` ensures the exported files are served directly.

This is a manual build snapshot from `kohmir/Grimfold` **main** at commit `baac2c10e4ae54c93e289301f5acb7a186204503` (Merge pull request #22). See `build-info.json` for the exported build settings. Import, all 1047 rules checks, additional Shop/relic/save-retry checks, startup, and Web release export passed with Godot 4.7.2.

Future source changes require a new export and upload here.
