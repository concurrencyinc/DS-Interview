Scripts written to set up PostgreSQL database - for other configurations see:
https://dataedo.com/samples/html/Dell_DVD_Store/doc/Dell_DVD_Store_12/modules/Dell_DVD_Store_database_diagram_107/module.html 

All C files in the data_files subdirectories have been pre-compiled - if running executables in 
these directories fails, recompile.

With local PostgreSQL server running execute:

sh pgsqlds2_create_all.sh 

to generate data, create database, and populate tables.
