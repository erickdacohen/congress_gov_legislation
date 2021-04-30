# China PP Congress.gov legislation

Project leaders: Shirley Han, Gifford Wong

The purpose of this script was to collect PDFs of legislation from [congress.gov](https://www.congress.gov/search?q={%22source%22:%22legislation%22}&searchResultViewType=expanded) relating to China.

The results are exported to an excel file after clicking the *Download Results* button. 

# Notebooks

1. acquire_legislation_pdfs_with_cache.ipynb 
This notebook itterates through the exported excel file containing URLs from congress.gov, downloading the PDFs of the legislation if available. Run time may take hours.

2. acquire_legislation_pdfs.ipynb 
Previous version of *acquire_legislation_pdfs_with_cache.ipynb* ; without the option to cache.

3. china_legislation_eeqa.ipynb
This notebook uses ktrain's end-to-end question answering capability to ask questions of the legislation. 


