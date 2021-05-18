# pgp-mo

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/pgp-missouri-2016-precincts-and-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.


## File processing:

- `MO_PGP_replication_file.ipynb`
  - processing file for reproducing PGP’s MO shapefile
  
- `file-processing` - folder that contains PGP-provided scripts used to replicate PGP's shapefile
  
  within `file-processing`:
    - `prec_to_blocks.py`
      - assigns block-group GEOIDs to blocks
    - `areal_interpolation.py`
      - dissolves census blocks by precinct labels. See PGP's documentation on setting up [areal interpolation](https://github.com/PrincetonUniversity/gerryspam/tree/master/General/areal_interpolation)
    -`clean.py`
      - creates final precinct shapefile

- verification
  - folder that contains verification replication file (`MO_verify.ipynb`) and report outputs
  
## Raw from source: 

- All raw data, output data (folder with the data created using PGP's scripts), replication shapefile, and PGP's shapefile are stored on AWS. (available upon request)


