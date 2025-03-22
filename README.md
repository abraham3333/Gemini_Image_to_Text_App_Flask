# Gemini Image to Text App

This project is a Flask web application that leverages the Google Gemini API to generate text responses based on text prompts.

## Description

The Gemini Image to Text App allows users to interact with the Google Gemini API through a simple web interface. Users can enter text prompts, and the application will send these prompts to the Gemini API, which will then generate corresponding text responses. The main functionality is to demonstrate the capabilities of the Gemini API in a web-based environment.

## Features

-   **Text Prompt Input:** Users can enter custom text prompts.
-   **Gemini API Integration:** The application sends prompts to the Gemini API and displays the generated text responses.
-   **Simple Web Interface:** Built with Flask, providing a user-friendly experience.

## Getting Started

### Prerequisites

-   Python 3.x
-   pip (Python package installer)
-   A Google Gemini API key

### Obtaining a Gemini API Key

1.  Go to the [Google AI Studio](https://makersuite.google.com/app/apikey) page.
2.  Click on "Get API key".
3.  Copy the generated API key.

### Installation

1.  Clone the repository:
```
bash
    git clone https://github.com/abraham3333/Gemini_Image_to_Text_App_Flask.git
    
```
2.  Navigate to the project directory:
```
bash
    cd Gemini_Image_to_Text_App_Flask
    
```
3.  Create a virtual environment (recommended):
```
bash
    python3 -m venv .venv
    
```
4.  Activate the virtual environment:

    -   On Linux/macOS:
```
bash
        source .venv/bin/activate
        
```
-   On Windows:
```
bash
        .venv\Scripts\activate
        
```
5.  Install the required packages:
```
bash
    pip install -r requirements.txt
    
```
6.  Set your API key:
    - Due to security, this is not in the code.
    - Create a main.py file
    -  Add the following line to the top of your main.py file.
```
python
         os.environ["GOOGLE_API_KEY"] = "YOUR_API_KEY"
        
```
### Running the App

1.  Ensure you are in the project directory and have activated the virtual environment.
2.  Run the Flask app:
```
bash
    python main.py
    
```
3.  Open your web browser and go to `http://127.0.0.1:5000/` to access the app.

## Technologies and Libraries Used

-   **Flask:** A micro web framework for Python.
-   **Google Gemini API:** For generating text responses based on prompts.
-   **Python:** The primary programming language used.
-   **HTML/CSS/JavaScript:** For the frontend web interface.
-   **requests**: Package for making http requests to Gemini API.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, please feel free to open an issue or submit a pull request.

## License

[MIT License](LICENSE)
