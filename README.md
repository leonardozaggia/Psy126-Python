<div style="padding-top:1em; padding-bottom: 0.5em;">
<img src="logo.png" width =200 align="right" />
</div>

# Example README

## Online usage (recommended)

Course materials for the psy112 seminar of the Neurocognitive Psychology Master's course at the University of Oldenburg. The content should primarily be accessed from the online book.

If you host your book on GitHub pages, you can add the link to this button: [![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://mibur1.github.io/psy111/)

## Local usage

Running the book locally requires to first build the book from source:

```python
cd <path/to/book/>
pip install -r requirements.txt
jb build .
```

This will create the html files in the `_build/` folder. The book can then be used by opening the `_build/html/index.html` file in a browser. The *.ipynb* notebooks for the exercises are located in the `book/` folder and can can either be opened locally or through Google Colab.
