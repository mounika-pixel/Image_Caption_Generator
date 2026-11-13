# Image Caption Generator

This application uses Streamlit, Hugging Face Transformers, and PyTorch to generate captions for uploaded images.

## Features

- Upload JPG, JPEG, or PNG images.
- Generate captions with Hugging Face's `Salesforce/blip-image-captioning-base` model.
- Cache the model after its first load for faster subsequent captions.

## Installation

Install Python 3.9 or later, then install the dependencies:

```bash
pip install -r requirements.txt
```

## Run the application

```bash
streamlit run main.py
```

On the first run, Hugging Face downloads the captioning model. This may take a few minutes. The model is cached and reused on later runs.

## Usage

1. Upload a JPG, JPEG, or PNG image.
2. Select **Generate Caption**.
3. View the generated caption.

## Contributing

Contributions, issues, and feature requests are welcome.

## License

This project is licensed under the terms of the MIT license.
