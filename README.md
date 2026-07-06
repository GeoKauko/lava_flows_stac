# lava_flows_stac
Repository to create lava flow outlines in Iceland using STAC. Outlines are structured into a vector data cube.

## Create environment first with:

conda create -n eocube python=3.11 pystac-client odc-stac xarray dask rioxarray zarr matplotlib jupyterlab pytorch torchvision geopandas rasterio rioxarray scikit-image pip
pip install segmentation-models-pytorch

conda activate eocube
