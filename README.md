# **local_volume_database** 

### DESCRIPTION:

Database of local volume dwarf galaxies and MW star clusters. The database is complete for dwarf galaxies within ~3 Mpc. 
The planned limiting distance is ~10 Mpc (i.e. resolved stars with HST or JWST).  
The star cluster collections are currently limited to star cluster/globular clusters in the MW halo and does not include open clusters.  

The main data tables are in the data/ folder in csv and fits format. 
There is a summary table of the database at [link](https://github.com/apace7/local_volume_database/blob/main/table/lvdb_table.pdf).

Documentation: [readthedocs](https://local-volume-database.readthedocs.io/en/latest/index.html)

The tables can be directly loaded into jupyter notebooks without having to download the repository:

    import astropy.table as table
    dwarf_mw = table.Table.read('https://raw.githubusercontent.com/apace7/local_volume_database/main/data/dwarf_mw.csv')


### ACKNOWLEDGEMENT:

If you use this in your research please include a link to the github repository (https://github.com/apace7/local_volume_database) and cite the database paper (once it is written). 
An example in latex is: This work has made use of the local volume database\footnote{\url{https://github.com/apace7/local_volume_database }}.

### INSTALLATION:
Todo.

The data is available as csv files (and other files)
