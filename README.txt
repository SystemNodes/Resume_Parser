##Resume Parser App

This is a Streamlit app that parses resumes in PDF, DOCX, or text format and extracts key information such as name, contact, email, experience, and skills.

#Features

- Upload multiple resumes at once
- Supports PDF, DOCX, and text file formats
- Extracts name, contact, email, experience, and skills from resumes
- Displays parsed data in a table

#Usage

1. Upload one or more resumes using the file uploader
2. The app will parse the resumes and display the extracted data in a table
3. If a resume fails to parse, an error message will be displayed

#Dependencies

- Streamlit
- Pandas
- PyMuPDF (for PDF parsing)
- docx (for DOCX parsing)
- Spacy (for natural language processing)
- re (for regular expressions)

#Note

- This app uses a simple approach to parsing resumes and may not work for all resumes.
- The parsing algorithm can be improved by adding more patterns and rules.
- This app is for demonstration purposes only and should not be used for production purposes without further development.