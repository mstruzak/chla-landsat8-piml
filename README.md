## Chlorophyll-a Retrieval from Landsat 8 using Physics-Informed MLPs
Data driven ML methods vs physics-informed MLP for chlorophyll-a retrieval from Landsat 8 surface reflectance using AquaSat matchup data.

### Data
Download AquaSat v1 (Ross et al., 2019) from Figshare:
[AquaSat](https://doi.org/10.6084/m9.figshare.8139383)
Update `df_fp` in the notebook to point to your local copy of `sr_wq_rs_join.csv`.

Download HUC-4 Chesapeake Bay Watershed .shp (US Fish and Wildlife Service):
[watershed](https://gis-fws.opendata.arcgis.com/datasets/chesapeake-bay-watershed-boundary/explore?location=39.826191%2C-77.565341%2C5)
Update 'chesapeake' in the notebook under "regional experiment" to your local copy of the .shp.

### Requirements
See requirements.txt. Developed and tested in Google Colab.

### Usage
Open in Google Colab and run cells top to bottom.
