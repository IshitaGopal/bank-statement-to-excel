# Bank Statement to Excel Converter
An application to convert bank statements into excel. Includes functionality to extract bank statements from:
1. Revolut 
2. Amex 


## Project Structure 
```
├── README.md            <- The top-level README and usage instructions.
├── data
│   ├── input            <- Immutable input data (PDF bank statements)
│   └── output           <- Generated outputs (parsed Excel files)
├── extractors           <- Code for use in this project.
│   ├── base.py          <- Base extractor class defining shared utilities  
│   ├── amex.py          <- Extractor implementation for American Express statements
│   └── revolut.py       <- Extractor implementation for Revolut statements     
├── main.py              <- Entry point for running the PDF-to-Excel extraction pipeline
├── notebooks            <- Jupyter notebooks.
│   └── test.ipynb       <- Scratch notebook for testing 
├── pyproject.toml       <- Project configuration and dependency management
└── uv.lock              <- Locked dependency versions for reproducible environments

```



