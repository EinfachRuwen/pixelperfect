# PixelPerfect

PixelPerfect is a user-friendly web application for optimizing and uploading images. It offers smart resizing and compression options to ensure your images are perfectly suited for web use.

## Features

- **Drag and Drop**: Easy image upload via drag and drop or file selection.
- **Multiple Optimization Methods**: 
  - Original: Uploads the image without changes.
  - Smart: Optimizes the image for best quality with reduced size.
  - Compact: Applies strong compression for minimal file size.
- **Real-time Preview**: See your image before uploading.
- **One-Click Upload**: Quickly upload your optimized image to a server.
- **Instant Link Sharing**: Get a shareable link immediately after upload.
- **Console Logging**: Track operations with a built-in console.

## How to Use

1. Open the PixelPerfect web page.
2. Drag an image onto the dropzone or click to select a file.
3. Choose an optimization method (Original, Smart, or Compact).
4. Click "Upload" to process and upload your image.
5. Copy the provided link to share your optimized image.

## Technical Details

- Built with vanilla JavaScript, HTML, and CSS.
- Uses the Canvas API for image processing.
- Implements async/await for smooth file handling and uploads.
- Responsive design for use on various devices.

## Setup

1. Clone this repository.
2. Open `index.html` in a web browser.
3. Configure the `ZIPLINE_SERVER_URL` in the script for your upload server.

## Contributing

Contributions to PixelPerfect are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
