# Process time series of TIF inundation data over Bangladesh

This collection of notebooks contains the step to download, process and extract statistics as well as visualisations from a time series of inundation data contained in `.tif` files.
The data to be processed has been generated by [Giezendanner et al. (2023)](https://ieeexplore.ieee.org/document/10208542).

The notebooks are organised as follow:
1. Download the tif collection [`0_DownloadTifCollection.ipynb`](./0_DownloadTifCollection.ipynb)
2. Create a zarr file [`1_CreateZarr.ipynb`](./1_CreateZarr.ipynb)
3. Download shapefile [`2_DownloadShapefile.ipynb`](./2_DownloadShapefile.ipynb)
4. Extract stats as a csv file for selected districts [`3_ExtractDistrcitsStatsAsCSV.ipynb`](./3_ExtractDistrcitsStatsAsCSV.ipynb)
5. Create a time series figure [`4_CreateTimeSeriesVisualisation.ipynb`](./4_CreateTimeSeriesVisualisation.ipynb)
6. Use the images generate in point 5 and create a movie [`5_CreateMovie.ipynb`](./5_CreateMovie.ipynb)

## Output

The code generates
- a `.csv` file containing the summary statistics for the districts (example in [OutputExample/DistrictInundationValues.csv](./OutputExample/DistrictInundationValues.csv)).
- a time series movie (example in [OutputExample/timeSeries.mp4](OutputExample/timeSeries.mp4))

https://github.com/GieziJo/GeospatialTools/assets/4385118/11174afb-92e5-4b73-af11-9404b7c3a341