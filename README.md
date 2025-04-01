# AI-powered Resume Screening and Ranking System

## Overview
The **AI-powered Resume Screening and Ranking System** automates the evaluation and ranking of resumes based on job descriptions. It helps recruiters efficiently shortlist candidates by leveraging **Natural Language Processing (NLP)** techniques.

## Features
- **Automated Resume Screening**: Extracts text from PDF resumes.
- **Job Relevance Ranking**: Uses **TF-IDF and Cosine Similarity** for ranking.
- **Bias Reduction**: Ensures a fair and efficient screening process.
- **User Interface**: Built with **Streamlit** for easy visualization.

## Technologies Used
- **Python 3.x**
- **PyPDF2** (PDF text extraction)
- **Scikit-learn** (TF-IDF, Cosine Similarity)
- **Streamlit** (Interactive UI)
- **Pandas, NumPy** (Data handling and numerical operations)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/AI-Resume-Screening.git
   cd AI-Resume-Screening
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   venv\Scripts\activate     # For Windows
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```
2. Upload resumes in PDF format.
3. Enter the job description.
4. View ranked resumes based on relevance.

## Future Enhancements
- Support for **multi-format resumes** (DOCX, images, etc.)
- Integration with **Applicant Tracking Systems (ATS)**
- Advanced **deep learning models** for improved accuracy
- **Bias detection and mitigation** features

## Contributing
Pull requests are welcome! Please follow best coding practices and submit improvements.

## License
This project is licensed under the MIT License.

## Contact
For any queries, contact **Raghu Ebbili** at [raghuraghava118@gmail.com](mailto:raghuraghava118@gmail.com).

