# GeminiDecode-Multilanguage-Document-Extraction-by-Gemini-Pro

GeminiDecode is a cutting-edge solution designed to extract and process data from documents in multiple languages with unparalleled efficiency. Leveraging advanced natural language processing (NLP) and machine learning algorithms, it seamlessly identifies, extracts, and categorizes information from diverse document formats, ensuring accuracy and speed. Ideal for global businesses, GeminiDecode supports over 50 languages, providing robust data extraction capabilities that streamline workflows, enhance productivity, and improve decision-making processes.

Features

Multilanguage Support: Extracts data from documents in over 50 languages. Advanced NLP and ML: Utilizes cutting-edge natural language processing and machine learning algorithms. Efficiency and Accuracy: Ensures high accuracy and speed in data extraction and processing. Versatile Document Formats: Supports diverse document formats.

Project Flow

User Interaction: The user interacts with the UI to enter the input. Data Transmission: User input is collected from the UI and transmitted to the backend using the Google API key. Model Processing: The input is forwarded to the Gemini Pro pre-trained model via an API call. Result Generation: The Gemini Pro pre-trained model processes the input and generates the output. Output Display: The results are returned to the frontend for formatting and display.

Requirements

To run this project, you need to have: Python 3.x installed on your machine. A valid Google API key for accessing the Gemini API.

Create a .env file in the project root directory and add your Google API key:

GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY

Install the required libraries:

pip install -r requirements.txt

Usage

Run the Streamlit application: streamlit run app.py Open your web browser and navigate to http://localhost:8501. Upload a PDF document and enter your prompt to extract information.
