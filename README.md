[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/4223)

# Singularity-Hub Recipies for R IDEs
These recipies should support running R-base, RStudio-Server and Jupyter-Notebooks

The port and settings of rstudio-server can easily be changed by re-binding the rstudio_conf folder to /etc/rstudio.
To change the port to 5555, just add "www.port=5555" to "rstudio_conf/rserver.conf" and start the container with:

singularity -B rstudio_conf:/etc/rstudio Xentrics/jupyter-r-base:rsudio-erver

