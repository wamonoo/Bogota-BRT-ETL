# Bogota-BRT-ETL
Extract, transform and load 2100 fixed width text files into PostgreSQL database. These cover a point in time ridership information covering the BRT's over 190 stations. 
In total the database had over 88.2 million rows of data. It took about 258 minutes to load the prepped dataframe into PostgreSQL

The general format of the data is of the form indicated below. Each file may have repeating headers and extra columns. Columns of interest are the ones shown in the extract.

CODIGOESTACION                         NUMEROMOLINETE                         FECHAINICIAL        FECHAFINAL          S   CANTIDAD
-------------------------------------- -------------------------------------- ------------------- ------------------- - ----------
12000                                  1211201                                01-04-2010 04:00:00 01-04-2010 04:14:59 S          1
12000                                  1211201                                01-04-2010 05:45:00 01-04-2010 05:59:59 E          3
12000                                  1211201                                01-04-2010 06:00:00 01-04-2010 06:14:59 E          3
