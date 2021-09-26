# Introduction
This system uses Questgen for predicting Questions and Answers. Questgen uses T5, BERT, and OpenAI GPT-2 for predicting questions and answers.

# Required Libraries
1. Flask
```python
pip install Flask
```
2. PyPDF2
```python
pip install PyPDF2
```
3. docx
```python
pip install python-docx
```
4. nltk
```python
pip install nltk
```
5. Questgen
```python
pip install git+https://github.com/ramsrigouthamg/Questgen.ai
pip install git+https://github.com/boudinfl/pke.git

python -m nltk.downloader universal_tagset
python -m spacy download em
```
6. sense2vec
```python
wget https://github.com/explosion/sense2vec/releases/download/v1.0.0/s2v_reddit_2015_md.tar.gz
tar -xvf  s2v_reddit_2015_md.tar.gz
```
7. fpdf
```python
pip install fpdf
```
8. os
```python
pip install os
```
# Change the directories and files
1. Line 11, changing the location of Sense2Vec
2. Line 14, change the line of UPLOAD_FOLDER
3. Line 146, change the location of the folder where the questions.pdf is saved

# Types of Questions
Our system generates the following types of questions
1. Boolean Questions
2. One word answers
3. Multiple Choice Questions
4. True and False
5. Breif Answer Questuons

# Types of Inputs
1. Text Input
2. Upload PDF
3. Upload Word Document

# Types of Output
1. Questions and Answers
2. Download pdf
