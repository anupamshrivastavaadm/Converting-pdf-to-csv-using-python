# Converting-pdf-to-csv-using-python

To convert a PDF file to a CSV file using Python, using tabula-py library.

In this code, I have first imported the tabula library. Then set the path to the PDF file which i want to convert. After that use the read_pdf function from tabula to extract all tables from the PDF file, and then using loops to loop through each table and convert it to a CSV file using the to_csv method. The index=False parameter is used to exclude the index column in the CSV file.

"Note : tabula-py requires Java to be installed on the system."
