FROM rocker/verse:devel
MAINTAINER "Carl Boettiger" cboettig@ropensci.org

RUN apt-get update \
  && apt-get install -y --no-install-recommends \
    lbzip2 \
    libfftw3-dev \
    libgdal-dev \
    libgeos-dev \
    libgsl0-dev \
    libgl1-mesa-dev \
    libglu1-mesa-dev \
    libhdf4-alt-dev \
    libhdf5-dev \
    liblwgeom-dev \
    libproj-dev \
    libnetcdf-dev \
    libsqlite3-dev \
    libssl-dev \
    libudunits2-dev \
    tk-dev \
    unixodbc-dev \
  && install2.r --error \
    RColorBrewer \
    RandomFields \
    classInt \
    deldir \
    gstat \
    lidR \
    mapdata \
    maptools \
    mapview \
    proj4 \
    raster \
    rgdal \
    rgeos \
    rlas \
    sf \
    sp \
    spacetime \
    spatstat \
    spdep \
    geoR \
    geosphere \
    ## from bioconductor
<<<<<<< HEAD
    && R -e "BiocInstaller::biocLite('rhdf5')" \
## Install additional R packages 
    ## from Github
    && installGithub.r \
    sboysel/boysel \
    sboysel/africa \
    sboysel/murdock \
    hannesmuehleisen/MonetDBLite

=======
    && R -e "BiocInstaller::biocLite('rhdf5')"
>>>>>>> 4e4486299e955243b98a91422d8fa2c315c0a5df
