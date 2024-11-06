Files for answering questions from jena-fuseki support

What kind of Update statements do you make to the triple store?

---------------------------------------------------------------

I have about 940 000 triplets in 374 named graphs, thus about 2500 triples for each ng.

ng_ktutk.txt and ng_teul.txt are just examples of my ngs and queries_ktutk_teul.txt has the sparql-queries executed at update of ktutk_teul.xlsx (, that has been committed to here as a csv-file )

The whole excel has about 29000 rows and the update happens in similar way as update of ktutk_teul.xlsx.

File memory_measurements.txt includes memory measurements from the host machine during 31.10.2024 - 4.11.2024. 

To see what happened there during that time search for key-word 'upload' from the file.
Uploads happened using jena-fuseki in podman user space containers and always the same python code with the same excel file as input.