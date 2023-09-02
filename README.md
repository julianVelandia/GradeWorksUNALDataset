# GradeWorksUNALDataset [WIP]
Dataset of the Grade Works of the UNAL repository.
Link repository: https://repositorio.unal.edu.co/handle/unal/5
Dataset kaggle: https://www.kaggle.com/datasets/juliancamilovelandia/trabajos-de-grado-repositorio-unal
The dataset currently has 1907 Grade Works extracted from a PDF (Each) saved in a JSON file, where the key is the file uri and the content is the entire PDF as plain text.

To do
* The dataset only contains the uri and all the text of the PDF, the data will be organized so that they contain these fields:
   ** Qualification
   ** Faculty
   ** Meta data
* Read the table of contents from each PDF and organize each field in the table as a field in the dataset
* More types of files, sql, csv etc...
