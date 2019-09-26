# A loneliness prescription index for the UK
This code is based on [an approach developed by the Office for National Statistics' Data Science Campus](https://datasciencecampus.ons.gov.uk/developing-a-loneliness-prescription-index/), which uses GP prescription data to find areas with above-average prescriptions for five conditions where loneliness has been shown to be a risk factor: Alzheimer's, depression, high blood pressure, anxiety and insomnia.

## Viewing the maps
The `Maps` sub-folder contains two PDFs:

- `Loneliness - whole UK.pdf`: showing the loneliness index for the whole UK
- `Loneliness - whole UK - above-average risks only.pdf`: showing the loneliness index only for areas that are at above-average risk of loneliness

## Making your own maps
Shapefiles and a .csv file containing the loneliness prescription index for Middle Layer Super Output Areas (England/Wales), Intermediate Zones (Scotland) and Super Output Areas (Northern Ireland) are in each country's sub-folder within this repository.

## Running the code
Before running the code, you'll need to download prescription and GP surgery data for each of the UK nations. Instructions for this is in each country's `Loneliness Process Data...ipynb` file. Once you've copied the data into the relevant sub-folders of each country's folder (again, see comments in the code for details), run the `Loneliness Process Data...ipynb` file to generate the loneliness prescription index. Afterwards, run `MSOA Mapping...ipynb` to produce the shapefiles (you'll also need to download the MSOA [or equivalent] shapefiles first).
