# Multilingual Text to Image/Video Generator

## Overview

The **Multilingual Text to Image/Video Generator** is a Python-based application that generates images and videos from textual descriptions in multiple languages. Utilizing state-of-the-art machine learning models like Stable Diffusion, this project enables users to create media content from natural language inputs across various languages, making it accessible to a global audience.

## Features

- **Multilingual Support**: Generate images and videos from text descriptions in multiple languages using the Google Translate API.
- **Image and Video Generation**: Create high-quality images and short videos using advanced diffusion models.
- **User-Friendly Interface**: Interact with the application via a simple Streamlit-based web interface.
- **Customizable Parameters**: Adjust various parameters for image and video generation to suit specific needs.

## Technologies Used

- **Python**: The core programming language for the application.
- **Streamlit**: A web application framework to create interactive web interfaces.
- **Diffusers**: A library for diffusion models, such as Stable Diffusion.
- **Transformers**: A library for natural language processing.
- **Google Translate API**: Provides multilingual support for text input.
- **FFmpeg**: A tool for video processing.

## Installation

To install and run the project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/multilingual-text-to-image-video-generator.git
    cd multilingual-text-to-image-video-generator
    ```

2. **Create a virtual environment:**

    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Install `localtunnel` globally (optional for web access):**

    ```bash
    npm install -g localtunnel
    ```

## Usage

To start the application, run the following command:

```bash
streamlit run app.py
```

## Some sample images

