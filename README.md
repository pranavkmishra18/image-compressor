# Image Compressor

A browser-only image compressor for GitHub Pages. Select or drop an image, choose JPEG quality, preview the result and download it. Images are processed locally with the browser Canvas API; they are not uploaded to a server.

## Publish with GitHub Pages
1. Create a GitHub repository named `image-compressor`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. The URL will be `https://YOUR-USERNAME.github.io/image-compressor/`.

## Notes
- Output is JPEG; transparent areas are flattened onto white.
- The quality slider controls JPEG encoding quality, not image dimensions.
- Very large images may require substantial browser memory.
