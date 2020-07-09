# Particle Analysis Scripts for AFM Data

These scripts were developed by Christopher W Wood and Harriet Reid. The scripts were
created to perform particle analysis on AFM data, and enable more complex analysis than
was possible on the software that came with the instrument.

# Publication

_More details soon._

# Running the Scripts

The code is provided in two Jupyter Notebooks which perform the analysis and create
plots for the 1hr and 24hr data. To recreate this analysis you can setup exact same
Python environment used to perform this analysis using the `conda_environment.yml` file
and the [Anaconda Python distribution](https://www.anaconda.com/products/individual).
For details of how to do that, see [this guide](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file).

After your environment is setup, you'll need to decompress the data
(`proximally-pinned-_pep-HP-TD_prox-*-flat-data.txt.gz`) and then you can launch a
Jupyter notebook server and open the `.ipynb` files.
