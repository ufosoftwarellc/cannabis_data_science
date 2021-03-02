# Starter Notebooks
These notebooks are a quick start Jupyter Notebooks for reading the December 2020 WA State Traceability Data.  The notebooks read in the CSV files and drops the depreciated columns.

Pandas is not able to read the Inventories_0.csv and Plants_0.csv files without special handling because they have partial columns.  The notebooks read only the valid columns using the usecols parameters of the read_csv function.


## Data Sources
[December 2020 WA State Traceability Data](https://lcb.app.box.com/s/fnku9nr22dhx04f6o646xv6ad6fswfy9?page=1)
[WA Traceability Data Guide](https://lcb.wa.gov/sites/default/files/publications/Marijuana/traceability/WALeafDataSystems_UserManual_v1.37.5_AddendumC_LicenseeUser.pdf)
