
# NLP-AI-Resume-Analyzer

This project will help all organizations which will hire there employees.

This Streamlit App has two section:

```
* First: is for Analyzing the Resume
* Admin
```

Through this app we will able to extract:
* Basic info of the candidate.
* experience level.
* Current skills.
* What type of job A candidate is looking for.
* recommend the courses according the current skills to enhance there skills more.
* Resume Score.
* recommend the youtube video to how to create the resume.
* recommend the youtube video how to prepare for the interview.

In the Admin section of the App you will able to see the data to the resume which is processed.

## Modules used:
* streamlit
* pandas
* base64
* time
* datetime
* random
* pyresparser
    * ResumeParser
* pdfminer3
    * layout
        * LAParams
        * LTTextBox
    * pdfpage
        * PDFPage
    * pdfinterp
        * PDFResourceManager
        * PDFPageInterpreter
    * converter
        * TextConverter
* io 
* random
* streamlit_tags
* PIL
* pafy
* plotly
* nltk

## To Run Resume Analysis
run a following command in terminal of pycharm
```
Streamlit run App.py
```
## Deployment
```
1. Load the necessary Modules
2. Define the function for the youtube video to fetch.
3. Define a function which is Generating a link allowing the data in a given panda dataframe to be downloaded.
4. Define a function which will read the resume pdf
5. And extract the valuable info from that.
6. Define a function which will show the pdf of the resume.
7. define a function for the courses recommendation.
8. connect to the sql database to store the processed resume information.
9. And after fetch the information just display on the streamlit App.
9. Push the code on the github.
```


## Demo

![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/NLP-AI-Resume-Analyzer/main/Untitled1.png)
![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/NLP-AI-Resume-Analyzer/main/Untitled2.png)
![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/NLP-AI-Resume-Analyzer/main/Untitled3.png)
![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/NLP-AI-Resume-Analyzer/main/Untitled4.png)
![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/NLP-AI-Resume-Analyzer/main/Untitled5.png)
