# Business-Documents-Repository-for-AI
This repository is a community place for gathering pointers to Business Documents that are available for use in R&amp;D and machine learning and AI projects. The goal of this effort is to foster sharing business documents in support of machine learning and AI research in Document Intelligence topics.


## Table of contents
1. [General (assorted forms)](#formsassorted)
2. [Receipts](#receipts)
3. [Tax Forms](#taxforms)
4. [Invoices](#invoices)
5. [Scientific Docments](#scidocs)
6. [Mixed Semi-structured](#mixedsemistruct)
7. [Mixed All Types](#mixedsemistruct)
7. [Tables](#tables)


## General (Assorted) Forms <a name="formsassorted"></a>

- FUNSD <br>
**URL**: https://guillaumejaume.github.io/FUNSD/ <br>
Desc:  The dataset comprises of 199 real-wold fully annotated, scanned forms. The forms are selected from RVL-CDIP dataset, which is in turn  subset of the Truth Tobacco Industry Document (TTID). The dataset is broken into a training set consisting of 149 forms, and 50 testing documents. <br>
Tasks: OCR, text detection, question answering, entity (sequence) labeling, entity linking. <br>
Labels: There are 4 main labels on the span of text in the documens, i.e., header, question, answer, and other.  <br>

- XFUND <br>
**URL**: https://github.com/doc-analysis/XFUND <br>
Desc: XFUND is a multilingual form understanding benchmark dataset that includes human-labeled forms with key-value pairs in 7 languages (Chinese, Japanese, Spanish, French, Italian, German, Portuguese). <br>
Tasks: Semantic Entity Recognition, Relation Extraction.<br>
Labels: Header,	Question,	Answer,	Other<br>

- NAF (National Archives Forms) Dataset<br>
**URL**: https://github.com/herobd/NAF_dataset <br>
Desc: The goal of this data is to capture relationships between text/handwriting entities on form images.<br>
Tasks: Semantic Entity Recognition, Relation Extraction. <br>
Labels: Label, Value (key - value). <br>

- GHEGHA Dataset<br>
**URL**: https://machinelearning.inginf.units.it/data-and-tools/ghega-dataset <br>
Desc:  The dataset contains two groups of documents: 110 data-sheets of electronic components and 136 patents. Each group is divided in classes: data-sheets classes share the component type and producer; patents classes share the patent source.<br>
Tasks: OCR, Semantic Entity Recognition, Information Extraction. <br>
Labels: Document Classes, data-sheets: Model, Type, Case, Power Dissipation, Storage Temperature, Voltage, Weight, Thermal Resistance;
Patents: Title, Applicant, Inventor, Representative, Filing Date, Publication Date, Application Number, Publication Number, Priority, Classification, Abstract 1st line.<br>

## Receipts <a name="receipts"></a>

- SROIE (Scanned Receipts OCR and Information Extraction) <br>
**URL**: https://rrc.cvc.uab.es/?ch=13<br>
Desc:  This dataset is prepared for ICDAR 2019 Robust Reading Challenge on Scanned Receipts OCR and Information Extraction. The dataset is split into a training/validation set (“trainval”) and a test set. The trainval set consists of 600 receipt images and the “test” set consists of 400 images.<br>
Tasks: Text localization, OCR, key information extraction. <br>
Labels: <br>

- CORD ( A Consolidated Receipt Dataset for Post-OCR Parsing)<br>
**URL**: https://github.com/clovaai/cord<br>
Desc: 1000 Indonesian receipts collected from shops and restaurants.<br>
Tasks: Semantic entity labeling, Information Extraction. <br>
Labels: Fine-grained classes: five superclass and 42 subclass labels.<br>

- ExpressExpense Receipt Image Dataset<br>
**URL**: https://expressexpense.com/blog/free-receipt-images-ocr-machine-learning-dataset/. <br>
Desc: The (sample) dataset consists of 200 images of restaurant receipts. <br>
Tasks: OCR, Semantic Entity Labeling. <br>
Labels: Not Labelled. 

- ICPR2018 Receipt Image and OCR dataset<br>
**URL**: https://receipts.univ-lr.fr/
Descr: This dataset is currently composed of 1969 images of receipts and the associated OCR result for each.<br>
Tasks: OCR. <br>
Labels: Not labelled <br>

## Tax Forms <a name="taxforms"></a>
- Presidential Tax Returns <br>
**URL**: https://www.taxnotes.com/presidential-tax-returns <br>
Desc: Tax files from select presidential candidates from 1932 to present.
Tasks: OCR, information extraction, question answering.
Labels: unlabeled.

- NIST SD02 <br>
**URL**: https://www.nist.gov/srd/nist-special-database-2 <br>
Desc: The NIST Structured Forms Database or “SD-02” dataset is the consists of 5,590 pages of binary, black-and-white images of synthesized documents. The documents comprise tax forms from the IRS from 1988. <br>
Tasks: Entity Extraction <br>
Labels: <br>

## Invoices <a name="invoices"></a>
**URL**: <br>
Desc: <br>
Tasks: <br>
Labels: <br>

## Scientific Documents <a name="scidocs"></a>
- DocBank <br>
**URL**: https://github.com/doc-analysis/DocBank. <br>
Desc: The DocBank dataset includes 500K document pages (scientific articles), where 400K for training, 50K for validation and 50K for testing. <br>
Tasks: Document layout analysis tasks<br>
Labels: Abstract, Author, Caption Date,	Equation, Figure, Footer, List, Paragraph, Reference, Section, Table, Title.<br>


## Mixed (Semi-structured Only) <a name="mixedsemistruct"></a>
- RVL-CDIP(Ryerson Vision Lab Complex Document Information Processing)-I <br>
**URL**: https://www.cs.cmu.edu/~aharley/rvl-cdip/<br>
Desc: RVL-CDIP dataset consists of 400,000 grayscale images in 16 classes, with 25,000 images per class. There are 320,000 training images, 40,000 validation images, and 40,000 test images.<br>
Tasks: Document classification.<br>
Labels: 16 classes; Information in documents are not labelled.<br>

## Mixed (Unstructured and Semi-structured) <a name="mixedall"></a>
- DocVQA <br>
URL: <br>
Desc: <br>
Tasks: Question Answering <br>
Labels: <br>

- Kleister
URL: <br>
Desc: Non-disclosure agreements collected from the EDGAR database <br>
Tasks: Entity Extraction <br>
Labels: <br>


## Tables <a name="tables"></a>
- PublayNet <br>
**URL**: https://github.com/ibm-aur-nlp/PubLayNet. <br>
Desc: PubLayNet is a large dataset of document images (PubMed articles), of which the layout is annotated with both bounding boxes and polygonal segmentations. The annotations are automatically generated by matching the PDF format and the XML format of the articles in the PubMed Central Open Access Subset. <br>
Tasks: Page Segmentation, Table Detection <br>
Labels: Text, Table, Title, Picture<br>

- PubTabNet <br>
**URL**: https://github.com/ibm-aur-nlp/PubTabNet<br>
Desc: PubTabNet is a large dataset for image-based table recognition, containing 568k+ images of tabular data annotated with the corresponding HTML representation of the tables.<br>
Tasks: Table structure and cell Recognition <br>
Labels: HTML structure of Tables (header, row, columns) <br>

## Document Repositories
Name: UCSF Industry Documents Library
URL: http://industrydocuments.ucsf.edu/

