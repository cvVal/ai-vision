# AI-Vision

**Installation:**

1. **Prerequisites:** Make sure you have Python installed on your system. You can check by running `python --version` in your terminal. If you don't have it, download it from [https://www.python.org/downloads/](https://www.python.org/downloads/).
2. **Install Libraries:** Open your terminal or command prompt and navigate to the directory where your project files are located. Then, run the following commands one by one:

   ```bash
   pip install streamlit  # Installs Streamlit library
   pip install -q google.generativeai  # Installs Google Generative AI library (quiet mode to suppress output)
   ```

**Authentication:**

1. **Obtain API Key:** Visit [Get API key in Google AI Studio](https://ai.google.dev/) and create a project or select an existing one. Then, enable the Google Generative AI API and create an API key.

2. **Create Environment Variable File:**

   - Create a new file named `.env` in your project directory (the same directory where your Python script is located).
     **Note:** This file is hidden by default on most operating systems. You might need to enable viewing hidden files to see it.

   - Add the following line to the `.env` file, replacing `YOUR_API_KEY` with your actual API key obtained in step 1:

     ```
     GOOGLE_API_KEY=YOUR_API_KEY
     ```

**Running the App:**

1. Open your terminal or command prompt and navigate to your project directory.

2. Run the following command to start the Streamlit application:

   ```bash
   streamlit run ./project_talking_with_an_image.py
   ```

This will launch the Streamlit app in your web browser, allowing you to interact with the app.
