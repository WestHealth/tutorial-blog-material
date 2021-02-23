FROM jupyter/base-notebook
RUN conda install mamba --yes
RUN mamba install dash pandas geopandas jupyter-dash jupyter-server-proxy --yes
RUN pip install dash_extensions dash-leaflet
COPY notebooks /home/jovyan
