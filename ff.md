LINE CLASSIFICATION
=====================

### Bidirectional Encoder Representations from Transformers or BERT for short is a very popular NLP model from Google known for producing state-of-the-art results in a wide variety of NLP tasks.

The importance of Natural Language Processing(NLP) is profound in the Artificial Intelligence domain. The most abundant data in the world today is in the form of texts and having a powerful text processing system is critical and is more than just a necessity.

A->
--------

  

### 1) DATASET PREPARATION

*   Making the dataset input format which is suitable for BERT to perform.
*   Dataset will have id, data, label, category, tokens and split tokens.

B->
--------


### 1) LC MODEL

*   
*   

1.  References email-ids should not be annotated
2.  No linkedIn or any other link to be annotated

  

### 3) Phone\_number

*   Phone number of the person to which the resume belongs to.
*   Eg: +91 8445566789, 8445566789

  

### 4) Language

*   Languages mentioned in the Resume.
*   Eg: English, Hindi, Marathi

  

### 5) DOB\_DateRange

*   For Dates present in ‘Date Of Birth’ Section or mentioned birthdate.

  

### 6) Gender

*   Sex of the person to which the resume belongs to.
*   Eg: Male, Female

  

### 7) Marital\_Status

*   States whether a person is married or not.
*   Eg: Single, Married

  

### 8) Address\_Location

*   Contains resume holder’s personal address mentioned.
*   For eg: 1) 302, Ward-5A, Adipur – (Gandhidham), Kutch-370205, Gujarat 2) Mumbai 3) Pune

  

### 9) Course

*   It is the Degree/Subject/Course done by resume holder in educational purpose.
*   Eg: PGDM in Marketing / Business Analytics from Institute of Management

  

### 10) Institute

*   It is the institute in which the resume holder completed his education.
*   Eg: Institute of Management

1.  It should not have the professional organization he/she works.

  

### 11) Grade

*   Grade achieved by the resume holder. Can contain percentage, grades(A-Z), GPA/CGPA.
*   Eg: 6.7/10, 67%, ‘A’

  

### 12) Education\_Location

*   Contains resume holder’s location mentioned in the ‘Educational Details’ section.
*   For eg:1) Mumbai 2) Pune

  

### 13) Education\_DateRange

*   For Dates the resume holder has completed his/her education in the ‘Education Details’ section.

  

### 14) Designation

*   It is the current or all other past positions of that resume holder. Basically, in every resume, there’s a work experience section, where they have mentioned designation in that section.
*   Eg: Developer, Analyst, Sr. Analyst

  

### 15) Organization

*   It is the current or all other past organizations that the resume holder has worked for. Contains company names mostly.
*   Eg: Accenture, HSBC

  

### 16) Role\_Description

*   Should have the work description of the positions that the resume holder worked for an organization

  

### 17) Work\_Location

*   Contains resumes holder’s Work location mentioned in the ‘Work Experience’ Section.
*   For eg: 1) Mumbai 2) Pune

  

### 18) Work\_DateRange

*   For Dates that resume holder has worked for a specific organization/company in the ‘Work Experience’ section.

  

### 19) Main\_Skills

*   Skills mentioned in the ‘Skills’ section in the resume.
*   Eg: SKILLS: C++, Java, Python, Windows, MacOS

  

### 20) Work\_Skills

*   Skills mentioned in the Summary section or Resume Profile section. Can be mentioned separately or in a paragraph.

  

#### **Date Formats:**

*   dd/mm/yyyy
*   dd/mm/yy
*   dd month yy
*   dd month yyyy
*   month yy
*   month yy – month yy
*   year – year

**_For annotation use -> https://pastelcuberesumes.herokuapp.com/ In this-> Go to datasets: Start annotating using the labels that are already created. Delete the garbage txt files._**