# Toronto MSI Time Series Analysis

This repo contains files required to make predictions on Toronto MSI data,
for educational purposes.

## Requirements
You need a Python and Jupyter environment.

## Setup

After cloning the repo, (`git clone `) and installing the required repos in `requirements.txt`, start a Jupyter server in the root directory.

## Data Cleaning & First Look.

You can now use the notebooks.
`01.ProcessRawPDF` will download PDF files from TRREB into the folder `01.raw-pdf`. It will then export the PDFs into CSV format and put these files in `02.raw-data`.
`02.ProcessRawData` will combine all CSV files into one dataset and put it into `03.clean-data`.
`03.ExploratoryDataAnalysis` is for exploring the data to find any data errors and for visualization.

From this point onwards, you should be able to use the file `03.clean-data/hpi.csv` for analytics and machine learning.

Note that this has been tested in May 2021, and PDF files that come after will likely require additional data cleaning.

