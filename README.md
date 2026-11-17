# PDForge

PDForge is a browser-based PDF editor presented as a standalone HTML application. The repository currently contains two versions of the editor.

## Available builds

| File | Version shown in the application |
|---|---:|
| `PDForge (2).html` | v3.0 |
| `PDForge (1).html` | v2.0 |

The v3.0 file is the newer interface. Both files are standalone HTML documents; there is no npm project or build step in this repository.

## Features visible in the editor

- Open a PDF in the browser
- Navigate pages, zoom, and fit the document to the window
- Search for text and use find-and-replace controls
- Add annotations, drawings, shapes, highlights, and text
- Insert a signature or image
- Apply document stamps such as Approved, Rejected, Draft, and Confidential
- Rotate pages and use undo/redo controls
- Export the edited document as a PDF
- Use a split-editing view
- In v3.0, access an optional Gemini assistant and image-generation interface

The exact behaviour of each tool should be checked in the selected HTML build and in a browser with a representative PDF.

## Run locally

1. Download or clone this repository.
2. Open `PDForge (2).html` in a modern browser.
3. Choose **Launch Editor** and open a PDF.

The page loads PDF.js from a CDN, so an internet connection may be needed for that library to load. PDF files are selected in the browser rather than uploaded to a repository service.

## Optional Gemini features

The v3.0 interface includes Gemini-powered assistant and image-generation controls. These require a Gemini API key supplied at runtime. Never commit an API key, token, or other credential to this repository. Review the provider's current terms and usage limits before using an API key.

## Repository notes

- The two HTML files are versioned snapshots, not a source/build pipeline.
- No automated test suite is included.
- No backend or server-side account system is documented here.
- Before treating the editor as production-ready, test export fidelity, large PDFs, browser compatibility, and error handling with real documents.

## Author

Shivam Raghuvanshi

## License

No license file is currently present. Ask the repository owner before redistributing or reusing the code.
