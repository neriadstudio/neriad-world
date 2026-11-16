# NERIAD - The Living Cathedral 🌊

An experimental, interactive underwater fantasy world. Explore six destinations in the browser, or watch the two-minute cinematic tour, with generative audio.

## Credits and licence

NERIAD is an adaptation of [Abyssal Garden](https://github.com/Noniv/abyssal-garden) by Maksymilian Dendura, under the MIT License. The original author's copyright and licence are retained in `index.html` and `LICENSE`.

## Publish with GitHub Pages

1. Sign in to GitHub and create a **public** repository named `neriad-world` (or another name). Create it with a README if you like.
2. Upload **`index.html`**, **`LICENSE`**, and **`.nojekyll`** from this folder to the repository's root. You can also upload this README. Commit the changes to `main`.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Select **`main`** and **`/(root)`**, then click **Save**.
6. Once GitHub's deployment finishes, the site will normally appear at `https://YOUR-USERNAME.github.io/neriad-world/` (replace username and repo name). Check the actual URL displayed under **Settings → Pages** before sharing.

## Browser compatibility

The world requires WebGPU. Use the actual GitHub Pages HTTPS link, rather than a local file preview or an in-app document viewer. On iPhone and iPad, try Safari with iOS/iPadOS 26 or newer on a compatible device. On Android or desktop, try an up-to-date Chrome or Edge browser. WebGPU availability also depends on GPU and browser support; not every device is compatible.

## Testing before sharing

- Open the HTTPS link directly in Chrome on Android; load the world and test navigation.
- On an iPhone with iOS 26+, open the same link directly in Safari. If unavailable, compare with the original Abyssal Garden demo to diagnose device support.
- Watch the two-minute tour all the way through and check for camera clipping and smooth frame pacing; V6.13 tour rendering has not been independently certified on all devices.
- For performance, start on Low or Medium quality if loading is heavy.

This is a static website: no server, npm build or backend needed. Changes to the GitHub repository create future deployments; keep a local master copy before editing.
