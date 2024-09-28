# WaterMarkIt

WaterMarkIt is a simple web application that allows you to easily add watermarks to a list of images, convert them to JPG format, and download them as a ZIP archive. You can configure the watermark size and position and save these settings locally in your browser.

## Features

- Select or drag-and-drop images in various formats (JPEG, JPG, PNG, GIF, WEBP, AVIF).
- Apply a watermark to all selected images.
- Configure watermark size (5% to 30% of the image width).
- Choose the watermark position (bottom-left, bottom-right, top-left, top-right).
- Convert all images to JPEG format with transparent areas filled with white.
- Download all images with watermarks as a ZIP archive.
- Settings and watermark image are stored in the browser's local storage.

## Technologies Used

- **HTML5** for the structure of the page.
- **JavaScript (ES6)** for image manipulation and watermark processing.
- **JSZip** library for creating ZIP archives.
- **CSS3** for styling the page.

## Getting Started

### Prerequisites

- You only need a modern web browser that supports HTML5, Canvas, and JavaScript.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gurov/WaterMarkIt.git
   ```
2. Open the index.html file in your web browser.


### Usage
Open the web application.
Upload or drag-and-drop a watermark image (PNG format only).
Select images for processing (JPEG, JPG, PNG, GIF, WEBP, AVIF formats).
Adjust the watermark size using the percentage slider.
Choose the position for the watermark (four corners available).
Click "Process Images" to apply the watermark.
Download the processed images as a ZIP archive.

### Local Storage

WaterMarkIt stores the watermark image and user settings (size and position of the watermark) in the browser's local storage. These settings will be restored when the page is reloaded.

### License
This project is licensed under the MIT License. See the LICENSE file for details.

### Contributing
Feel free to submit issues or pull requests. Contributions are welcome!

### Acknowledgements
JSZip for ZIP archive functionality.

