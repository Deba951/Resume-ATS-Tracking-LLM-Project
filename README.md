# Smart ATS Resume Checker
Smart ATS is a Streamlit web application designed to help job seekers improve their resumes based on specific job descriptions. It leverages Google's Generative AI to act like an experienced Application Tracking System (ATS) and provide detailed feedback on resume matching, missing keywords, and profile summaries.

<img width="1296" alt="WorkFlow" src="https://github.com/Deba951/Resume-ATS-Tracking-LLM-Project/assets/83878346/d91a4ebc-14a0-4fec-a278-7b478e2164a6">

## Table of Contents
- [About the App](#about-the-app)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## About the App
The Smart ATS app takes a job description and a resume as inputs, evaluates the resume against the job description, and provides feedback on how well the resume matches the job description. The feedback includes a percentage match, a list of missing keywords, and a profile summary to help improve the resume.

## Prerequisites
Before running the app, ensure you have the following installed:
- Python 3.7 or later
- pip (Python package installer)
- Google API key for Generative AI (makersuite)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/smart-ats.git
    cd smart-ats
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up your environment variables:
    - Create a `.env` file in the project directory.
    - Add your Google API key to the `.env` file:
        ```
        GOOGLE_API_KEY=your_google_api_key_here
        ```

## Technologies Used
- **Streamlit**: An open-source app framework for creating web apps with Python.
- **PyPDF2**: A PDF toolkit for extracting text from PDF files.
- **google.generativeai**: Google's Generative AI for generating intelligent responses.
- **python-dotenv**: A module to load environment variables from a `.env` file.

### Brief Overview of Technologies
- **Streamlit**: Allows the creation of interactive web applications with minimal code, perfect for data-driven applications.
- **PyPDF2**: Helps in reading and extracting text from PDF files, which is crucial for processing resume files.
- **google.generativeai**: Provides advanced AI capabilities to simulate an ATS and generate detailed resume feedback.
- **python-dotenv**: Manages environment variables, keeping sensitive data like API keys secure and separate from the codebase.

## Usage
1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. Open your web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`).
You can also go ahead with the published link to test the application.

3. Use the interface to:
    - Paste the job description in the text area.
    - Upload your resume in PDF format.
    - Click the "Submit" button to receive feedback.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
