# AI-Powered Resume Screening and Ranking System
## Project Title & Description
The AI-Powered Resume Screening and Ranking System is a machine-learning-based tool designed to automate the resume screening process. The system takes a job description as input, processes multiple resumes, and assigns a ranking score to each based on its relevance to the job role. This helps recruiters quickly identify the most suitable candidates without manually reviewing each resume.

The project leverages Natural Language Processing (NLP) techniques to compare job descriptions with resume content, ensuring efficient and unbiased candidate evaluation.

## Features
Automated Resume Screening – Uses NLP to match resumes with job descriptions.
Ranking System – Assigns a relevance score to each resume.
Multiple Resume Uploads – Supports bulk PDF resume uploads.
User-Friendly Interface – Built with Streamlit for easy interaction.
Fast & Efficient – Reduces manual effort in hiring by automating the screening process.
Data Visualization – Displays ranked results in an intuitive format.

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
Python (3.x)
Git
pip (Python package manager)
Virtual Environment (optional but recommended)
### Clone the Repository
`git clone https://github.com/poojamarla/AI-Resume-Screening.git`
`cd AI-Resume-Screening`
### Install Dependencies
`pip install -r requirements.txt`
###  Run the Application
`streamlit run app.py`

## Usage Instructions
- Enter the Job Description in the text box.
- Upload Resumes (multiple PDFs).
- Click Submit to start the screening process.
- The system ranks resumes based on their relevance to the job description.
- The ranked list of resumes is displayed along with their scores.

## Technologies Used
+ Python – Core programming language
+ Streamlit – For the interactive web interface
+ Scikit-learn – Machine learning library for text processing
+ Pandas – Data handling and manipulation
+ NLTK / spaCy – Natural Language Processing (NLP)
+ PyMuPDF – To extract text from PDFs
+ Git & GitHub – Version control and repository management

## Screenshots/Demo
### Home Page
![Screenshot (703)](https://github.com/user-attachments/assets/87b1b36d-8c32-4ff9-aecc-59cdfa23b364)

### Input Phase
![Screenshot (701)](https://github.com/user-attachments/assets/cf08a174-a528-45c6-a121-2924b6f045ca)

### Output Phase
![Screenshot (702)](https://github.com/user-attachments/assets/462e5257-3896-4458-9df9-e610338a2b79)
