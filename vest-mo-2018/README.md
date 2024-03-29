# vest-mo-2018

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2018-missouri-precinct-and-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## **Raw from source:**
- File: VEST MO 18 data file
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?fileId=4366212&version=33.0)
  - AWS: `mo_2018.zip` (available upon request)
  - Accessed: 03/02/21
  - Note:

- File: VEST MO 18 documentation file
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?fileId=4366213&version=33.0)
  - AWS: `documentation.txt` (available upon request)
  - Accessed: 03/02/21
  - Note:

- File: MO Precinct-Level Election Results
  - Online: [Open Elections Github Link](https://github.com/openelections/openelections-data-mo/tree/master/2018)
  - AWS: `20181106__mo__general__precinct.csv` (available upon request)
  - Accessed: 03/03/21
  - Note:

- File: U.S. Census Bureau's 2020 Redistricting Data Program Phase 2 release
  - Online: [Missouri Page](https://www.census.gov/geo/partnerships/pvs/partnership19v2/st29_mo.html)
  - AWS: `2020_Phase_2` (available upon request)
  - Accessed: 03/03/21
  - Note: These can only be downloaded 5 at a time, I downloaded the data for all counties and then filtered down to the needed ones.

- File: 2010 Census VTD release
  - Online: [Census Link](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2010&layergroup=Voting+Districts)
  - AWS: `2010_VTD` (available upon request)
  - Accessed: 03/03/21
  - Note:  Monroe County is the only county from this source.

- File: 2020 Census VTD release
  - Online: [Census Link](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html)
  - AWS: `2020_VTD` (available upon request)
  - Accessed: 03/03/21
  - Note:  Downloaded the entire file for MO and filtered downn to Platte County, which is the only county from this source.

- File: Camden County Precincts (tif)
  - Online: [Link](https://camdengis.integritygis.com/H5/Index.html?viewer=camden)
  - AWS: `Camden` (available upon request)
  - Accessed: 03/09/21
  - Note: Unable to load this file in a reasonable amount of time due to the format  

- File: Cooper County Precincts (tif)
  - Online: [Link](https://coopergis.integritygis.com/H5/Index.html?viewer=cooper)
  - AWS: `Cooper` (available upon request)
  - Accessed: 03/09/21
  - Note: Unable to load this file in a reasonable amount of time due to the format  

- File: Marion County Precincts (tif)
  - Online: [Link](https://mariongis.integritygis.com/H5/Index.html?viewer=marion_public)
  - AWS: `Marion` (available upon request)
  - Accessed: 03/09/21
  - Note: Unable to load this file in a reasonable amount of time due to the format 

- File: Lafayette County Precincts (tif)
  - Online: [Link](https://lafayettegis.integritygis.com/H5/Index.html?viewer=lafayette)
  - AWS: `Lafayette` (available upon request)
  - Accessed: 03/09/21
  - Note: Unable to load this file in a reasonable amount of time due to the format 

- File: Laclede County Precincts (tif)
  - Online: [Link](https://lacledegis.integritygis.com/H5/Index.html?viewer=laclede)
  - AWS: `Laclede` (available upon request)
  - Accessed: 03/09/21
  - Note: Unable to load this file in a reasonable amount of time due to the format

- File: Bates County Precincts (tif)
  - Online: [Link](https://batesgis.integritygis.com/H5/Index.html?viewer=bates)
  - AWS: `Bates` (available upon request)
  - Accessed: 03/09/21
  - Note: Unable to load this file in a reasonable amount of time due to the format

- File: Audrain County Precincts (tif)
  - Online: [Link](https://audraingis.integritygis.com/H5/Index.html?viewer=audrain)
  - AWS: `Audrain` (available upon request)
  - Accessed: 03/03/21
  - Note: Unable to load this file in a reasonable amount of time due to the format

- File: Jasper County Precincts (shapefile)
  - Online: [Link](https://jaspercountymogisintiatives-jcmo.hub.arcgis.com/datasets/voting-precincts-2020)
  - AWS: `Jasper` (available upon request)
  - Accessed: 03/09/21
  - Note: Able to load this file

## File processing: 
- `vest-mo-2018-validation.ipynb` - documentation in comments and markdown cells