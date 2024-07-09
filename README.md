# Resume Parser

The Generative AI Resume Parser is an innovative application designed to revolutionize the resume parsing process using cutting-edge AI technology. Traditional parsers often struggle with diverse formats and nuanced language, leading to inaccuracies in extracting crucial information. This project addresses these challenges by harnessing Generative AI to intelligently interpret and extract data from a wide range of resume structures.

## Getting Started

### Virtual Environment

First, set up a virtual environment to manage dependencies. This helps maintain project consistency and avoid conflicts with other projects.

```bash
python -m venv venv
.\venv\Scripts\activate  # For Windows
source venv/bin/activate  # For macOS/Linux
```

Ensure all necessary dependencies are installed by running:

```bash
pip install -r requirements.txt
```

Then run the app using

```python
streamlit run app.py
```
  
  
<h2> Features</h2>

Here're some of the project's best features:

*   Advanced Data Extraction: Utilizes state-of-the-art Generative AI models to extract information from resumes accurately. This includes parsing personal details skills work experience education history and more even from resumes with non-standard formats.
*   Contextual Understanding: Goes beyond keyword matching by understanding the contextual meaning of phrases and sentences within resumes. This capability allows for a deeper understanding of the applicant's qualifications and experience.
*   Interactive User Interface: Features a user-friendly interface that allows recruiters or users to interact with the parsed data and validate results. This interface is designed to be intuitive and efficient catering to both technical and non-technical users.

  
  
<h2> Built with</h2>

Technologies used in the project:

*   Generative AI(Gemini)
*   Python
*   Streamlit


## Example Usage

### Parsing a Resume

1. Upload a resume file (PDF) through the application interface.
2. The AI parser processes the document and extracts relevant information such as contact details, skills, work experience, and education.
3. Users can review and verify the parsed information through the interactive dashboard.

## Future Enhancements

- **Integration with Job Portals**: Automatically parse resumes uploaded by job applicants on recruitment platforms.
- **Multilingual Support**: Extend parsing capabilities to support resumes in various languages.
- **Semantic Analysis**: Implement deeper semantic analysis to understand the context and intent behind resume content.
- **Performance Optimization**: Improve parsing speed and accuracy through model optimization and parallel processing.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please contact [Sarath Rajendran](mailto:sarath.rajendran.2021@gmail.com).
