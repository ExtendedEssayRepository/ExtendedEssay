# Extended Essay Repository
## This repository contains the source code and datasets used for my Extended Essay project. The code involves web scraping from CodeForces and extracting features. 

## Data Sources
This project utilizes data from the CodeComplex-Data repository.

Note: To maintain data integrity and respect licensing, the raw .jsonl files are not hosted here. To replicate this study, please download the original files from the CodeComplex repository and place them in the /data directory.

## How to Use
1. Clone the repository
2. Install dependencies: pandas, beautifulsoup4, playwright, and pylatexenc.
3. Check ## Data Sources to ensure necessary data is added.
4. Run DataMerger: Execute DataMerger.py to preprocess the JSONL data from the CodeComplex repository.
5. Run Extraction: Execute BuildDataset.py to process the merged JSONL data into the final CSV format.
