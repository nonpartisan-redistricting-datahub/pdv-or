# vest-or-2016

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-oregon-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## **Raw from source:**
- File: VEST OR 16 data file
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/NH5S2I/CEN9OL)
  - AWS: `or_2016.zip` (available upon request)
  - Accessed: 07/23/21
  - Note:

- File: VEST OR 16 documentation file
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?fileId=4938232&version=65.0)
  - AWS: `documentation.txt` (available upon request)
  - Accessed: 07/23/21
  - Note:

- File: OR 16 Precinct-Level Results
  - Online: [Open Elections](https://github.com/openelections/openelections-data-or/)
  - AWS: `Open_Elections` (available upon request)
  - Accessed: 07/23/21
  - Note:

- File: OR 16 Precinct Shapefile
  - Online: [Kevin Rancik's Personal Website](http://www.kevinrancik.com/elections/Oregon/eOregon.html)
  - AWS: `Shapefile` (available upon request)
  - Accessed: 08/24/21
  - Note: This was not the sourcefile that VEST mentioned, but it appears to match up very closely to VEST's file.

- Note: VEST's documentation describes a number of sourcefiles used to generate their shapefile, because we were able to find a separate shapefile, we did not go about reaching out to counties and attempting to recreate the shapefile ourselves.

## File processing

- `vest-or-2016-validation.ipynb` - documentation in markdown cells and comments
