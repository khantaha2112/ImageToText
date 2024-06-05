# ImageToText - IITD Assignment

Testing Video :

https://github.com/khantaha2112/ImageToText/assets/110721493/077dc52d-f5a8-4ecb-b059-e63156af1813

















ImageToText is a web application that utilizes Optical Character Recognition (OCR) technology to extract text from images. It provides a simple and intuitive interface for users to upload images, extract text, and optionally view bounding boxes for specific types of text elements such as words, lines, paragraphs, blocks, or pages.

## Features

- **Image Upload**: Allows users to upload images in various formats (e.g., JPEG, PNG).
- **Text Extraction**: Utilizes OCR technology to extract text from uploaded images.
- **Bounding Box Extraction**: Provides the option to extract bounding boxes for specific types of text elements (e.g., words, lines, paragraphs, blocks, pages).
- **User-friendly Interface**: Offers a simple and intuitive user interface for easy interaction.

## Installation

To run ImageToText locally on your machine, follow these steps:

### Prerequisites

- Node.js and npm installed on your machine.

### Clone the Repository

1. Clone the ImageToText repository to your local machine:

   ```bash
   git clone https://github.com/khantaha2112/ImageToText.git

2. Navigate to the project directory:
```bash
 cd ImageToText

* Install Dependencies
    Install the required npm dependencies by running the following command:

    ```bash
    npm install

* Start the Server
   Start the Node.js server by running:

 ```bash
 npm run start

* Access ImageToText
Once the server is running, you can access ImageToText in your web browser at http://localhost:5000


## Usage

 1. Upload Image: Click on the "Choose Image" button to select an image file from your computer. Supported image formats include JPEG, PNG, and others.
 2. Select Bounding Box Type (Optional): Choose the type of bounding boxes for text extraction from the dropdown menu. Options include words, lines, paragraphs, blocks, and pages.
 3. Extract Text: After uploading the image, click on the "Extract Text" button to initiate the text extraction process.
 4. View Results: Once the text extraction process is complete, the extracted text will be displayed on the screen. If you selected a bounding box type, you will also see the bounding boxes for the specified text elements.


### Technologies Used

Node.js: Server-side runtime environment.
Express.js: Web application framework for Node.js.
Multer: Middleware for handling file uploads.
Tesseract.js: OCR library for text extraction from images.
HTML, CSS, JavaScript: Frontend technologies for building the user interface.


 ### Acknowledgements
ImageToText was developed to provide a simple and efficient tool for extracting text from images using OCR technology.
Special thanks to the developers of the libraries and technologies used in this project.
