## Paraphrasing_Bot

### Project Overview

This project provides a web application that leverages OpenAI's GPT-4 Turbo model to paraphrase user-inputted text. The application is built using Streamlit, allowing for a simple and interactive user interface.

### Features

- **User Input**: Allows users to input text that they wish to be paraphrased.
- **Paraphrasing**: Generates four different paraphrased versions of the input text using GPT-4 Turbo.
- **Output**: Displays the original and paraphrased text in JSON format.

### Project Structure

- `main.py`: Main application file containing the Streamlit web app and logic for text paraphrasing.

### Dependencies

- Python 3.10
- Streamlit
- OpenAI Python client library

### Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/generate_paraphrasing.git
   cd generate_paraphrasing
   ```

2. **Create a virtual environment and activate it**
   ```sh
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages**
   ```sh
   pip install -r requirements.txt
   ```

4. **Set the OpenAI API key**
   - Open the `main.py` file and set your OpenAI API key in the `os.environ['OPENAI_API_KEY']` line.

### Running the Application

To run the Streamlit application, execute the following command:
```sh
streamlit run main.py
```
The application will start and open in your default web browser, listening on `http://localhost:8501/`.

### Usage

1. **Enter Text**: In the input text field, enter the text you want to paraphrase.
2. **Paraphrase**: Click the "Paraphrase" button to generate four different paraphrased versions of the input text.
3. **View Output**: The original and paraphrased text will be displayed in JSON format.

### Acknowledgments

- OpenAI for providing the GPT-4 Turbo model
- Streamlit for the web application framework


