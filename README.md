# fileMetadataChart

A browser-based utility that reads and preserves **file creation/modification date metadata**. Upload files, view their timestamps, edit them manually, and export a formatted PDF chart — useful before compressing archives, which often strips metadata.

## Features

- Drag-and-drop or click-to-browse file upload
- Automatically reads file modification timestamps
- Manually edit dates per file
- Remove individual files or clear all
- Export a formatted PDF with styled headers, alternating rows, and pagination
- Fully client-side — no data ever leaves your browser

## Tech Stack

- Vanilla JavaScript, HTML5, CSS3
- [jsPDF](https://github.com/parallax/jsPDF) v2.5.1 (via CDN)

## How to Use

1. Open `index.html` in any modern browser — no installation or server needed
2. Drag and drop files onto the page (or click to browse)
3. Review and edit dates as needed
4. Click **Export PDF** to download the chart

No internet connection is required.
