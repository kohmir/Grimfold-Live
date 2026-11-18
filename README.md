# Grimfold Live

Browser playtest build of Grimfold, exported with Godot 4.7.2.

## Play

https://kohmir.github.io/Grimfold-Live/

Open in a recent browser with WebGL 2 support. On iPhone Safari, landscape is recommended. The build uses single-threaded WebAssembly and includes mobile textures; real iPhone compatibility has not yet been verified.

## Hosting

In **Settings → Pages**, choose **Deploy from a branch**, **main**, **/ (root)**, then Save. `.nojekyll` ensures the exported files are served directly.

This is a manual build snapshot from `kohmir/Grimfold` **main** at commit `9151db4aefb1e994f8153ed46bb0b8e3e37dd7d1` (Merge pull request #12). See `build-info.json` for the exported build settings. Import, all 921 rules checks, startup, and Web release export passed with Godot 4.7.2.

Future source changes require a new export and upload here.
