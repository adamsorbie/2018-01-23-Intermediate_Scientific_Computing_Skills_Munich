# Python

## Repetition of basics

- See Jupyter Notebooks from [previous course](https://github.com/konrad/2017-03-29-Software_Carpentry_Munich_Teaching_Material/tree/master/Python/)

## Object oriented programming

- This is short introduction to understand classes and objects; the main goal is to
  understand how they are used later in packages like pandas.

- See Jupyter Notebook [Classes_introduction.ipynb](https://github.com/konrad/2018-01-23-Intermediate_Scientific_Computing_Skills_Munich/blob/master/Python/Classes_introduction.ipynb)

## Writing your own modules



## argparse - Adding nice command line interfaces to pyhton scripts

- [argparse documentation](https://docs.python.org/3/library/argparse.html)

## PEP 8 - coding style

- Style recommendation how to write your
  code:
  [PEP 8](https://www.python.org/dev/peps/pep-0008/#maximum-line-length)
- Most IDEs are supporting this an will highlight violations of these
  recommendations

## Python documentation in the command line

- the shell tool `pydoc`
  - e.g. `pydoc argparse`

## Pandas

- see Jupyter notebook `pandas_ecology_introduction.ipynb`, taken from http://www.datacarpentry.org/python-ecology-lesson/
- [pandas cheat sheet](https://github.com/pandas-dev/pandas/blob/master/doc/cheatsheet/Pandas_Cheat_Sheet.pdf)
 - [CSV](https://en.wikipedia.org/wiki/Comma-separated_values) / [TSV](https://en.wikipedia.org/wiki/Tab-separated_values)
 - Using "!" in jupyter to call Shell commands

### Question: How to deal with huge files in pandas

- run it on a machine with more RAM (e.g. see below - run it on a server)
- read the file in [chunks](https://stackoverflow.com/questions/25699439/how-to-iterate-over-consecutive-chunks-of-pandas-dataframe-efficiently)
- if possible use numpy instead
- if possible read the data into an SQL data base and access that from pandas

### Question: Can I run Jupyter on a server

- Yes [you can](https://jupyter-notebook.readthedocs.io/en/stable/public_server.html)!
- Maybe [port forward](https://www.ssh.com/ssh/tunneling/example) is needed

### Question: How to clean data

- maybe in pandas
- maybe before e.g. with sed in the Shell
- [OpenRefine](http://openrefine.org/)
- [Tidy data paper](http://vita.had.co.nz/papers/tidy-data.html)
- [Data organization in spreadsheets](https://peerj.com/preprints/3183/)

### Hint to avoid confusion - methods of Series and Dataframes

- some methods are implemented for Serie and for Dataframes e.g. apply
  - [pandas.DataFrame.apply](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.apply.html)
  - [Series.apply](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.apply.html)

## Visualization
Check out the example galleries
### [Seaborn](https://seaborn.pydata.org/)
- For statistical plots
- Very high-level interface
- Allows fast production of nice-looking plots
- Good integration with pandas

### [Matplotlib](https://matplotlib.org/)
- Allows very fine control over plots
- Takes a bit more effort to produce complex plots
- Is the backend behind seaborn
- Wide variety of plots possible

## Machine learning: scikit-learn
- [Iris data set](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data)
- See [Jupyter notebook]()


## Further useful Python libraries

- Biopython
- scikit-bio
- numpy
- scipy
- statsmodels

## Python IDEs (Selection)
- PyCharm
- Emacs (+ elpy)
- vim
- spyder
- Atom
- Sublime
- Jupyter Lab
- [VIM](https://realpython.com/blog/python/vim-and-python-a-match-made-in-heaven/)

### Useful IDE Features
- syntax highlighting
- autocompletion
- git integration
- remote working
