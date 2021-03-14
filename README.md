A single-page, one-column resume for software developers. It uses the base latex templates and fonts to provide ease of use and installation when trying to update the resume. The different sections are clearly documented and custom commands are used to provide consistent formatting. The three main sections in the resume are education, experience, and projects.

### 1. Motivation

The author created this template as managing a resume on Google Docs was hard and changing any formatting was too difficult since it had to be applied in multiple places. Most currently available templates either focus on two columns, or are multiple pages long. The author personally found the two-column templates hard to focus while multiple-page resumes were just too long to be used in career fairs.

### 2. Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex Nguyen-Quoc-Bao-CV.tex
```

### 3. Link to Overleaf

https://www.overleaf.com/read/byqctvsjtynr

### 4. Preview

![Resume Screenshot](/Nguyen-Quoc-Bao-CV.png)

### 5. License

This repo is created by Sourabh Bajaj at https://github.com/sb2nov/resume and updated by Quoc-Bao Nguyen. Format is MIT but all the data is owned by Quoc-Bao Nguyen. 
