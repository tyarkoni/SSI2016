# Introduction to Data Science in Python

This repository contains Jupyter notebooks, code samples, and all other materials used in the Intro to Data Science in Python course taught at the [2016 UT Summer Statistics Institute](https://stat.utexas.edu/training/ssi). Links to new sections or resources will be added below as content is added.

## Course overview/links

* [Day 1: The Python Data Science Stack](https://github.com/tyarkoni/SSI2016/blob/master/notebooks/Day%201%20-%20the%20Python%20data%20science%20stack.ipynb)
* [Day 2: Data munging](https://github.com/tyarkoni/SSI2016/blob/master/notebooks/Day%202%20-%20data%20munging.ipynb)

## Setup
To get the most out of the course, you'll probably want to show up to class with a laptop set up with a working scientific Python environment. The easiest way to accomplish this is to install the [Anaconda distribution](https://www.continuum.io/downloads), available for all major operating systems. You can install anaconda from:

    https://www.continuum.io/downloads

Anaconda comes prepackaged with many of the core scientific Python libraries, including numpy, scipy, pandas, scikit-learn, and Jupyter. However, there may be other packages we'll cover or use in the course. You should be able to install virtually all of these using the `conda` or `pip` installers. From the command prompt, type:

> conda install [package]

Or:

> pip install [package]

Packages we'll almost certainly work with (which you may want to install ahead of time) include `scikit-learn`, `seaborn`, `statsmodels`, and `rpy2`--all of which can be installed with `conda install` (e.g., `conda install seaborn`).

## Testing your environment

If you want to make sure you have a working scientific Python environment prior to the first day of class (recommended), you can try running the [test notebook](https://github.com/tyarkoni/SSI2016/blob/master/notebooks/test.ipynb) in this repository. You should be able to view the rendered notebook in your browser even if you don't run it, but I recommend downloading and executing the Jupyter notebook to make sure everything works. If you're familiar with GitHub, you can clone the entire repository and navigate to the notebook. If you're not, the easiest way to execute the notebook is to load the [raw notebook code available here](https://raw.githubusercontent.com/tyarkoni/SSI2016/master/notebooks/test.ipynb) in your browser, then save the file to a convenient location. Now, from the command line, navigate to the directory containing the saved notebook, and run:

> jupyter notebook test.ipynb

(If you saved the notebook under a different name, substitute for test.ipynb accordingly.)

After a few seconds, you should see a local version of the notebook open up in your browser. You should now be able to execute the entire notebook by selecting the "Run all" option from the dropdown "Cell" menu. If you run into problems, they'll almost certainly arise in the first code cell containing all of the import statements. The likely culprit is that you've failed to install one or more of the required Python packages, in which case you can go back to the previous section and make sure you've installed Anaconda as well as the other packages mentioned above. If you run into issues (and you're registered in the SSI course!), feel free to [email me](mailto:tyarkoni@gmail.com) with questions. If you don't run into any problems, congratulations! You're all set for the course.