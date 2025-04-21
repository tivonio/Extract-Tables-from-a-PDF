# Overview
PDF stands for “Portable Document Format.” It is the third most popular file format on the web (after HTML and XHTML). There are trillions of PDF files worldwide. Businesses and government agencies widely use PDFs to distribute information and collect data electronically. While it has become an essential part of business communication in the digital age, it is not necessarily a good format for working with data. Extracting tables from PDF files is a common need for businesses and researchers. It allows them to analyze and report on the data more effectively.

Extracting text from a PDF can be as simple as copying and pasting the content. However, extracting tabular data may not be as straightforward as table structure is rarely maintained and columns and rows get distorted. Fortunately, there are other methods we can use. Python, for example, has a variety of libraries available for extracting tables from PDF files. This project demonstrates how to extract tables from a PDF using the Camelot Python library.
## Data
The data source for this porject is the Annual City Budget data for Augusta, Georgia published as PDF files on www.augustaga.gov
## Process Outline
1. Install Python Libraries
2. Extract Tables
3. Pandas Dataframe
4. Data Validation
5. Save as CSV File
## Python Libraries
1. Camelot – Used for extracting tables
  * Works with text-based files and tables only
  *Required dependencies: Tkinter, Ghostscript
2. PyPDF2 – Different types of PDF operations
  * Auto-installed with Camelot
  * Defaults to v3.0, which has a deprecation error
  * Solution: pip install PyPDF<3.0
3. Pandas – Data manipulation and analysis
4. Matplotlib – Visualization and plots
5. NumPy – Scientific computing
