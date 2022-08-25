# Project-IR
Information Retrieval Project
Overview:
This project covers some areas of information retrieval. Examining the functional components of information retrieval including document and query representation, indexing techniques, similarity and matching, retrieval models, evaluation techniques, implementation issues, query reformulation (relevance feedback), Space models and space reduction.

Phase 1 StopList
Read data from the files, supported files :
Text Files
PDF files (PDF Reader Library)
Images ( All types of Images suppored by Tesseract-OCR -> Optical Charachter Recognition engine)
Removing stopwords and handling three symboles { @ . , }
Write data files results in STP directory as Text files
Phase 2 Stemming
Read data from STP directory
Removal of suffixes using Porter Stemmer Algorithm
Write the results in SFX directory as Text files
Phase 3 Inverted file
Read data from SFX directory
Initialize and fill the inverted file matrix
Detect the new stopwords
Phase 4 Query
Receive query from user
Initialize and fill the weighted query list
Rank the documents
Phase 5 Evaluation
Calculate Precision ,Recall ,and F-measure
System Requirements:
Java 13, you can download it from https://www.oracle.com/java/technologies/javase/jdk13-archive-downloads.html
PDF Reader Library, you can download it from https://downloads.apache.org/pdfbox/2.0.24/
Tesseract-OCR, you can download it from https://tesseract-ocr.github.io/tessdoc/Downloads.html
Directory Setup:
main path is "C:\Users\LENOVO\Desktop\IR"

~\data
contains test collection

~\dataStpresults
contains files with stop words removed

~\dataSfxresults
contains files after stemming

~\packages\Tesseract-OCR
contains all the .exe files of the search engine

~\packages\Tesseract-OCR\temp
contain one text file "imageOutText.txt" that contain engine's result
