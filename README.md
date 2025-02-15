# Resume Parser and Scoring Web App

A Django-based web application designed to parse and score resumes based on predefined skill criteria. The app uses Python's `pdfminer` library to extract text from PDF resumes, analyzes the content, and scores the resumes based on the skills defined in an XML file.

## Features

- **Resume Parsing**: Extracts text from PDF resumes using `pdfminer`.
- **Skill Scoring**: Scores resumes based on predefined skill keywords stored in an XML file.
- **Customizable Criteria**: Easily modify the XML file to define or update the skills and keywords for scoring.
- **User-Friendly Interface**: Simple and intuitive web interface to upload and analyze resumes.

## How It Works

1. The user uploads a resume in PDF format.
2. The app extracts text from the PDF using `pdfminer`.
3. The extracted text is analyzed against the skill keywords defined in the XML file.
4. The resume is scored based on the presence and relevance of the skills.
5. The results are displayed to the user.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- Django
- pdfminer.six (`pip install pdfminer.six`)

## How to Run the Project

Follow these steps to set up and run the project locally:

### Step 1: Create a Virtual Environment

Create a virtual environment to manage dependencies:
python -m venv {Environment Name}

### Step 2: Activate the Virtual Environment

Activate the virtual environment:

- On Windows:
  {Environment Name}\Scripts\activate

- On macOS/Linux:
- source {Environment Name}/bin/activate

### Step 3: Install Dependencies 

### Step 4: Run the Django Server
Start the Django development server:

```bash
python manage.py runserver
