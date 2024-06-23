```markdown
# Language Nexus

Language Nexus is a Streamlit-based web application that provides a variety of language-related functionalities, including translation, dyslexia-friendly text conversion, and word cloud generation. This application aims to make language translation and accessibility easy and efficient.

## Features

1. **Translation**: Translate text from one language to another with text-to-speech functionality.
2. **Dyslexia-Friendly Text Conversion**: Convert regular text into a format that is easier to read for individuals with dyslexia.
3. **Word Cloud Generation**: Generate and visualize word clouds from the input text.
4. **About Us**: Information about the Language Nexus team and their mission.

## Getting Started

### Prerequisites

To run this application, you need to have Python installed on your system along with the necessary libraries. You can install the required libraries by running the following command:

```sh
pip install -r requirements.txt
```

### Running the Application

1. **Clone the repository**:
    ```sh
    git clone https://github.com/VishnuSwaroop-PS/LanguageNexus.git
    cd LanguageNexus
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv env
    source env/bin/activate   # For Windows use `env\Scripts\activate`
    ```

3. **Install the dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the application**:
    ```sh
    streamlit run translator.py
    ```

## File Structure

- `translator.py`: The main source code file containing the implementation of the Language Nexus app.
- `requirements.txt`: The file containing the list of dependencies required for the app.

## Usage

Upon running the application, you will be presented with a sidebar for navigation and several options:

1. **Translate**: 
   - Enter text to translate.
   - Select the target language.
   - View the detected language, translated text, and listen to audio versions of both.

2. **Dyslexia**:
   - Enter text to convert into a dyslexia-friendly format.
   - View the converted text.

3. **Word Cloud**:
   - Enter text to generate a word cloud.
   - Visualize the generated word cloud.

4. **About Us**:
   - Learn about the team behind Language Nexus and their mission.

## Dependencies

The application requires the following Python libraries:

- `streamlit==1.5.0`
- `Pillow==9.0.0`
- `gtts==2.2.2`
- `googletrans==4.0.0-rc1`
- `numpy==1.22.0`
- `wordcloud==1.8.1`
- `matplotlib==3.5.1`

These dependencies can be installed using the `requirements.txt` file provided.

## Screenshots

![Language Nexus Screenshot](images/screenshot.png)

## Contact

For any questions or suggestions, feel free to reach out to us at example@example.com.

---

Thank you for using Language Nexus!
```
