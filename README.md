# Grade Works UNAL Dataset

![image](https://github.com/user-attachments/assets/1bdcd3f3-0a06-48f0-94cf-f96a7acdd767)


Dataset of the Grade Works of the UNAL repository.

Link repository: https://repositorio.unal.edu.co/handle/unal/5

Dataset kaggle: https://www.kaggle.com/datasets/juliancamilovelandia/trabajos-de-grado-repositorio-unal

The dataset currently has 1907 Grade Works extracted from a PDF (Each) saved in a JSON file, where the key is the file uri and the content is the information of the tesis and the entire PDF as plain text.

# Format dataset.json
```json
{
  "uri":{
    "advisor": "Herrera León, Fernando Augusto",
    "author": "Téllez González, Jonathan Salvador",
    "date": "2023-08-11",
    "description": "La finalidad del trabajo presente es...",
    "title": "Diseño de iluminación, control y embellecimiento...",
    "program": "Bogotá - Ingeniería - Especialización en Iluminación Pública y Privada",
    "faculty": "Facultad de Ingeniería",
    "raw_content": "Diseño de iluminación, control y\nembellecimiento de la cancha..."
  }
}
```

# To do

* Read the table of contents from each PDF and organize each field in the table as a field in the dataset
  
* More types of files, sql, csv etc...
