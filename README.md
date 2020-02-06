# Getting started with acoustic well log data using the dlisio Python library on the Volve Data Village dataset

This repository contains the [companion Jupyter
Notebook](https://github.com/equinor/dlisio-notebooks/blob/master/acoustic.ipynb)
to the article [Getting started with acoustic well log data using the dlisio
Python library on the Volve Data Village
dataset](https://www.researchgate.net/publication/340645995_Getting_started_with_acoustic_well_log_data_using_the_dlisio_Python_library_on_the_Volve_Data_Village_dataset)
by Erlend Magnus Viggen, Erlend Hårstad, and Jørgen Kvalsvik, published in
April 2020 as part of the Proceedings of the 43rd Scandinavian Symposium on
Physical Acoustics.


## How to run the notebook locally

```bash
git clone https://github.com/equinor/dlisio-notebooks.git
cd dlisio-notebooks
pip install -r requirements.txt
jupyter notebook
```

The file used in this notebook is from the Volve field, which was made publicly
available by Equinor in 2018. The file, along with the rest of the Volve data
can be downloaded from [here](https://data.equinor.com). Specifically, the
notebook uses the well integrity log file
`WL_RAW_PROD_AC-AIMG-CCL-GR_2013-06-05_2.DLIS` from well F-11 B.
