These are the complete clinical and temporal annotations for 1000 publicly available VAERS reports, prepared as part of the joint FDA/CDC project to create a Clinical Langauge Engineering Workbench (CLEW) that would provide various clinical natural language processing tools for different types of clinical data as publicly available web services.

The ".db" file is a SQLite database containing report information along with the annotations. They can be found in the ETHER_ANNOTATIONS and ETHER_TIME_ANNOTATIONS tables in the database.

The ".csv" files are exports of the relevant information from those two database tables. Annotated clinical features can be found in the Clinical Annotations file and temporal features can be found in the Temporal Annotations file. The clinical-temporal associations that link them are contained in the Clinical Annotations file, where the TIME_ID column contains a number that maps to the ANNOTATION_ID of the temporal feature in the Temporal Annotations file for the same report number (or VAERS_ID).

For a complete description of the creation of this annotated data set, please see:

   Foster M, Pandey A, Kreimeyer K, Botsis T. Generation of an annotated reference standard for vaccine adverse event reports. Vaccine 2018 Jul 5;36(29):4325-4330.

   https://doi.org/10.1016/j.vaccine.2018.05.079


Note: adverse event narratives are truncated.
