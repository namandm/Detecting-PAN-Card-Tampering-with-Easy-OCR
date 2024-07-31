# Detecting-PAN-Card-Tampering-with-Easy-OCR

The **Detecting-PAN-Card-Tampering-with-Easy-OCR** project extracts text from Pan Card images using Optical Character Recognition (OCR). Users can upload Pan Card images through an easy-to-use interface, and the app will process these images to extract and display the text in a clear format.

## Key Features

- **Text Detection:** Uses the EasyOCR library to accurately detect text in Pan Card images.
- **User Interface:** Built with Streamlit, it lets users upload images and view the extracted text easily.
- **Preprocessing:** Enhances image quality for better text extraction, including contrast adjustment and rotation correction.
- **Bounding Box Visualization:** Shows where the text is detected on the image to help understand the OCR results.
- **Data Extraction:** Filters out unnecessary information and presents only key details from the Pan Card.
- **Data Presentation:** Displays the extracted text in a structured format for easy reading and analysis.

## Libraries Used

- **Streamlit:** For the user interface and file uploads.
- **OpenCV (cv2):** For image processing like converting to grayscale and rotating images.
- **Pandas:** For organizing and structuring the extracted text data.
- **Matplotlib:** For showing bounding boxes on the image.
- **EasyOCR:** For performing OCR on the Pan Card images.

## Project Components

- **tamp_detection.py:** Contains functions for preprocessing images, performing OCR, filtering text, and visualizing bounding boxes.
- **app.py:** Main script using Streamlit to handle user interactions and display results.

## Installation

1. **Install Dependencies:** Run the following command in your terminal:
   ```bash
   pip install -r requirements.txt
   ```
## Run Locally

Clone the project

```bash
  git clone https://github.com/namandm/Detecting-PAN-Card-Tampering-with-Easy-OCR.git
```

Go to the project directory

```bash
  Pan-Card-Tampering-Detection-using-easyOCR-final
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server

```bash
  streamlit run app.py
```


