# ResizePDF

ResizePDF is a fast, private, browser-based image toolkit.

## Features

- Resize images with exact dimensions and aspect-ratio locking
- Compress JPG, PNG, and WebP files
- Convert between JPG, PNG, and WebP
- Create multi-image PDFs in the browser
- Drag-and-drop and multi-file workflows
- No uploads, accounts, analytics, or server-side image processing

## Run locally

pnpm install
PORT=23248 BASE_PATH=/ pnpm --filter @workspace/resize-pdf run dev

Then open http://localhost:23248.

## Build

PORT=23248 BASE_PATH=/ pnpm --filter @workspace/resize-pdf run build

The app processes normal image files in the browser. See the Privacy page in the app for the full data-handling explanation.
