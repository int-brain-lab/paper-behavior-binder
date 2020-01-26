# A standardized and reproducible method to measure decision-making in mice: Data

The data can be downloaded at: https://figshare.com/articles/A_standardized_and_reproducible_method_to_measure_decision-making_in_mice_Data/11636748

The data is contained in NumPy `.npy` files organized in a hierarchy of subfolders following this structure: `/{lab}/Subjects/{subject}/{date}/{number}/alf/`

You can use the ONE interface to load the data in Python. The script `one_example.py` shows an example of searching and retrieving the data locally. You need Python 3.6+ and ibllib 1.4.7+. ibllib depends on a number of packages, including NumPy, SciPy, pandas, matplotlib. At the moment we recommend that you install ibllib in a fresh Python environment, as follows: `virtualenv ibl`, `source ibl/bin/activate`, `pip install ibllib`.

To launch the script, go into the data directory named `ibl-behavior-data-Dec2019`, and type `python one_example.py`. This script will only work if you launch this command from within that directory, as the ONE loader takes the current directory as data source by default.
