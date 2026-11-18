# Grimfold Live

Browser playtest build of Grimfold, exported with Godot 4.7.2.

## Play

Once GitHub Pages is enabled: https://kohmir.github.io/Grimfold-Live/

Open in a recent browser with WebGL 2 support. On iPhone Safari, landscape is recommended. The build uses single-threaded WebAssembly and includes mobile textures; real iPhone compatibility has not yet been verified.

## Hosting

In **Settings → Pages**, choose **Deploy from a branch**, **main**, **/ (root)**, then Save. `.nojekyll` ensures the exported files are served directly.

This is a manual build snapshot from source commit `750d82aca605a3865b04d0f850432081cd9d751f`, including the new imbuement card backgrounds. Future source changes require a new export and upload here.
