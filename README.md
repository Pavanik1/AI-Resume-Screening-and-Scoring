AI Resume Screening & Candidate Ranking System  
Overview  
This AI Resume Screening & Candidate Ranking System is a web-based application built using Streamlit that ranks resumes based on their relevance to a given job description. It uses Natural Language Processing (NLP) and Cosine Similarity with TF-IDF (Term Frequency-Inverse Document Frequency) to compare resumes against the job description and assign scores.

Features  
Upload multiple resumes in PDF format  
Extract text from PDF resumes  
Analyze resumes based on the provided job description  
Rank candidates based on their similarity score  
Display the ranked resumes in a table format

      
Technologies Used    
Python  
Streamlit (for the web interface)  
PyPDF2 (for PDF text extraction)  
Scikit-learn (TF-IDF Vectorization and Cosine Similarity)  
Pandas (for tabular data representation)  



How to Use  
Open the application in your browser.  
Enter the job description in the text area.  
Upload one or more PDF resumes using the file uploader.  
Click the Submit button.  
The app will display a ranked list of resumes with their similarity scores in a table format.  


Future Enhancements  
Add Skill Extraction using Named Entity Recognition (NER)  
Generate PDF reports with the ranking results  
Support for DOCX files  
Interactive Dashboard Visualizations  

