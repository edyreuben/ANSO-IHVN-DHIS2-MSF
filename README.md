ANSO-IHVN-DHIS2-MSF
====================

A web-based data validation tool for verifying IHVN Monthly Summary Forms (MSFs) submitted to DHIS2. This application helps M&E teams and data managers ensure accuracy, completeness, and consistency of reported health data.

Features
--------
- Secure integration with DHIS2 API using Basic Authentication
- Dynamic data validation for HTS, PMTCT, AGYW, KP and other service areas
- Interactive user interface with ipywidgets
- Excel, Word, and PDF report generation
- HTML-to-Image export support for visual dashboards
- Compatible with Jupyter and Voila for dashboard deployment

Dependencies (requirements.txt)
-------------------------------
requests
pandas
numpy
ipywidgets
openpyxl
python-docx
html2image
Pillow
pdfkit

Note: Some libraries used in the project (e.g., os, sys, re, functools, getpass, urllib.parse) are part of Python’s standard library and do not require installation.

How to Run
----------
1. Clone the repository:
   git clone https://github.com/yourusername/ANSO-IHVN-DHIS2-MSF.git
   cd ANSO-IHVN-DHIS2-MSF

2. Install the dependencies:
   pip install -r requirements.txt

3. Launch the app (optional, if using Jupyter Voila):
   voila app.ipynb

Project Structure
-----------------
src/                  - Main Python scripts
assets/               - Images or styling files
app.ipynb             - Main interactive notebook
requirements.txt      - List of required Python packages
README.txt            - Project description and setup guide
