# Comic Book Creator

## Overview
The **Comic Book Creator** is a Streamlit-based web application that generates AI-powered comic-style images, analyzes their content, and converts the generated story into speech using Clarifai's AI models. This app integrates OpenAI and Clarifai APIs for image generation, text analysis, and text-to-speech conversion.

## Features
- **Image Generation**: Creates a comic-style image based on user input using DALL·E.
- **Image Understanding**: Analyzes the generated image and produces a creative story.
- **Text-to-Speech (TTS)**: Converts the generated story into speech output.
- **User-Friendly UI**: Built with Streamlit for seamless interaction.

## Requirements
Before running the application, ensure you have the following:

- Python 3.8+
- Required Python libraries (see installation steps)
- API keys for Clarifai and OpenAI

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Deepanshu-DA/Comic_Book_Creator.git
   cd Comic_Book_Creator
   ```

2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory and add:
   ```env
   CLARIFAI_PAT=your_clarifai_api_key
   OPEN_AI=your_openai_api_key
   ```

## Usage
Run the Streamlit app using the following command:
```sh
streamlit run main.py
```

## File Structure
```
Comic Book Creator/
│── main.py              # Main application script
│── requirements.txt      # Python dependencies
│── .env                 # API keys (not included in the repository)
│── README.md            # Project documentation
```

## Technologies Used
- **Streamlit** - For UI development
- **Clarifai API** - For AI-based image generation and text-to-speech
- **OpenAI GPT-4 Vision** - For image understanding
- **Pillow** - For image handling

## Acknowledgments
Special thanks to Clarifai and OpenAI for their powerful AI models that make this project possible.

## License
This project is licensed under the MIT License.

