# Grade Works UNAL Dataset

Dataset of the Grade Works of the UNAL repository.

Link repository: https://repositorio.unal.edu.co/handle/unal/5

Dataset kaggle: https://www.kaggle.com/datasets/juliancamilovelandia/trabajos-de-grado-repositorio-unal

Dataset HuggingFace: https://huggingface.co/datasets/JulianVelandia/unal-repository-dataset

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

The extraction process is as follows

![image](https://github.com/user-attachments/assets/a81d8a9d-4112-4ddd-bec8-325435c21c2a)

![image](https://github.com/user-attachments/assets/fe10e284-fb28-463c-b52e-805456cea7a7)

## Key Statistics of `dataset.json`

- **Total records**: 1910  
- **Total extracted texts (`raw_content`)**: 1859  
- **Unique programs**: 54  
  - Most frequent program: **Medicine - Specialization in Anesthesiology** (995 records)  
- **Unique advisors (`advisor`)**: 664  
  - Most frequent advisor: **Narváez Rincón, Paulo César** (82 records)  
- **Unique authors (`author`)**: 1863  
  - Most frequent author: **Campos Gaona, Rómulo** (4 records)  
- **Unique years (`date`)**: 533  
  - Most frequent year: **2014** (182 records)  
