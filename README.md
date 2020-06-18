# Python Idioms

A presentation on writing "pythonic" code.

## Opening the notebook

To run the jupyter notebook (Python Idioms.ipynb), Anaconda is required.

When Anaconda is installed, navigate to the notebook directory and run the following in a terminal:

```powershell
conda activate base

jupyter notebook
```

## Viewing the slides

The presentation slides are available by opening Python Idioms.slides.html in a web browser.

To build the slides from scratch, run the following in a terminal:

```powershell
conda activate

jupyter nbconvert "Python Idioms.ipynb" --to slides --post serve
```
