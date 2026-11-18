# Grimfold Live

Browser playtest build of Grimfold, exported with Godot 4.7.2.

## Play

https://kohmir.github.io/Grimfold-Live/

Open in a recent browser with WebGL 2 support. On iPhone Safari, landscape is recommended. The build uses single-threaded WebAssembly and includes mobile textures; real iPhone compatibility has not yet been verified.

## Hosting

In **Settings → Pages**, choose **Deploy from a branch**, **main**, **/ (root)**, then Save. `.nojekyll` ensures the exported files are served directly.

This is a manual build snapshot from `kohmir/Grimfold` **main** at commit `efa3851133050b52050a09abedffb1d891537941` (Merge pull request #14). See `build-info.json` for the exported build settings. Import, all 1035 rules checks, startup, and Web release export passed with Godot 4.7.2.

Future source changes require a new export and upload here.
