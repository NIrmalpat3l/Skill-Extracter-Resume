Resume Skill Extractor

This repository contains a Python script for extracting skills from resumes in PDF format. The script uses OCR (Optical Character Recognition) to convert resume pages into text and then identifies specific skills from the text.
Features

    PDF to Image Conversion: Converts each page of a resume PDF into an image.
    OCR with Tesseract: Extracts text from the images using Tesseract OCR.
    Skill Identification: Searches for and identifies predefined skills from the extracted text.
    Customizable Skill List: Easily modify the list of skills to suit your specific needs.

Installation

To run the script, you'll need to install the required dependencies. Use the following commands:

bash

pip install pytesseract
apt-get install tesseract-ocr
pip install pdf2image
apt-get install poppler-utils

Usage

    Place your resume PDF: Replace Path_to_resume_file in the script with the path to your resume PDF file.
    Run the script: The script will convert the PDF pages to images, extract text from them, and identify skills based on the predefined list.
    Output: The identified skills will be printed in the terminal.

Example

python

pdf = r"Path_to_resume_file"

# Add your list of skills to match
skills = ["Python", "Java", "C++", "SQL", "JavaScript", "HTML", "CSS", "Machine Learning", "Data Science", "Project Management", "Communication", "Leadership", "Teamwork", "Problem Solving", "Time Management", "Adaptability", "Creativity", "Networking", "Linux", "AWS", "Docker", "Kubernetes", "Git", "Agile", "Scrum"]

# Run the script and identify skills from the resume

Dependencies

    Python 3.x
    Tesseract OCR
    pdf2image
    PIL (Pillow)

Contributing

Feel free to contribute by adding new features, improving the skill identification logic, or optimizing the code. Please create a pull request for any changes you'd like to contribute.
License

This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments

    Tesseract OCR for OCR functionality.
    pdf2image for converting PDF files to images.

You can copy and paste this into your README.md file in your GitHub repository.
