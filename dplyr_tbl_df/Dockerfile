FROM rocker/r-base

RUN Rscript -e 'install.packages("versions");library(versions);install.versions("dplyr", "0.4.2");install.packages("tidyr")'

CMD ["R"]