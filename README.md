# Social Image Toolkit

A responsive browser-based editor for preparing images for social platforms. Images are processed locally in the browser; no application server receives your selected files.

## Features
- Instagram post, Story and Reel presets; Facebook post and cover; LinkedIn post and banners; YouTube thumbnail and channel art.
- Custom dimensions up to 10,000 × 10,000 pixels, optional locked aspect ratio.
- Cover/contain fitting, zoom, horizontal and vertical positioning.
- Background color and text overlays with size, weight, alignment, color, position and shadow.
- PNG, JPEG and WebP export.
- Batch resize multiple images and download as ZIP.
- Responsive layout and light/dark theme.

## Run locally
Open `index.html` in a modern browser or serve this folder with a static HTTP server. No build step is required. ZIP export uses JSZip from jsDelivr; Google Fonts and JSZip CDN requests require an internet connection.

## Privacy and limitations
- Images are decoded and processed in the browser; they are not uploaded to an application backend.
- Batch ZIP export requires JSZip CDN access.
- Large images/batches may use substantial device memory.
- This is a raster editor and does not preserve editable layers or vector source data.
- Batch export applies image fit, zoom, position and background settings. Text overlay applies to the primary preview/export only.
- Presets are common canvas sizes, not a guarantee of current platform safe areas or display behavior.

## Deployment
Publish the repository root with GitHub Pages.

## License
No license has been specified yet.