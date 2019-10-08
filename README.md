# Bogota-BRT-ETL
Extract, transform and load 2100 fixed width text files into PostgreSQL database. These cover a point in time ridership information covering the BRT's over 190 stations. 
In total the database had over 88.2 million rows of data. It took about 258 minutes to load the prepped dataframe into PostgreSQL

Each file may have repeating headers and extra columns. Columns of interest are CODIGOESTACION, NUMEROMOLINETE, FECHAINICIAL, FECHAFINAL, S, CANTIDAD

Use the nb viewer link below for a static version if the ipynb file is not rendered directly in github
https://nbviewer.jupyter.org/github/wamonoo/Bogota-BRT-ETL/blob/master/Bogota_BRT_etl.ipynb
