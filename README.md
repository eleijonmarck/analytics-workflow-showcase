#[Data-mining and Machine Learning with Python](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
#### *Using Python*


The Bayesian method is the natural approach to inference, yet it is hidden from readers behind chapters of slow, mathematical analysis. The typical text on Bayesian inference involves two to three chapters on probability theory, then enters what Bayesian inference is. Unfortunately, due to mathematical intractability of most Bayesian models, the reader is only shown simple, artificial examples. This can leave the user with a *so-what* feeling about Bayesian inference. In fact, this was the author's own prior opinion.


<div style="float: right; margin-left: 30px;"><img title="created by Stef Gibson"style="float: right;margin-left: 30px;" src="http://i.imgur.com/6DKYbPb.png?1" align=right height = 350 /></div>
Contents
------

See the project homepage [here](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/) for examples, too.


The below chapters are rendered via the *nbviewer* at
[nbviewer.ipython.org/](http://nbviewer.ipython.org/), and is read-only and rendered in real-time.
Interactive notebooks + examples can be downloaded by cloning! 


* [**Chapter 1: Introduction to Bayesian Methods**](http://nbviewer.ipython.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter1_Introduction/Chapter1.ipynb)
    Introduction to the philosophy and practice of Bayesian methods and answering the question, "What is probabilistic programming?" Examples include:
    * Inferring human behaviour changes from text message rates


Installation and configuration
------

Minimum
[Download python for your operating system](https://www.python.org/downloads/)

* From powershell do the following
* ````powershell
python get-pip.py
```

* Install via [brew (MAC OSX)](http://brew.sh/)
* ```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

If you would like to run the IPython notebooks locally, (option 1. above), you'll need to install the following:

-  IPython 0.13+ is a requirement to view the ipynb files. It can be downloaded [here](http://ipython.org/ipython-doc/dev/install/index.html) 
- Necessary packages are Pandas, NumPy, SciPy and Matplotlib.   
   -  For Linux/OSX users, you should not have a problem installing the above, [*except for Matplotlib on OSX*](http://www.penandpants.com/2012/02/24/install-python/).
   -  For Windows users, check out [pre-compiled versions](http://www.lfd.uci.edu/~gohlke/pythonlibs/) if you have difficulty. 
   - also recommended, for data-mining exercises, are [PRAW](https://github.com/praw-dev/praw) and [requests](https://github.com/kennethreitz/requests). 
- New to Python or IPython, and help with the namespaces? Check out [this answer](http://stackoverflow.com/questions/12987624/confusion-between-numpy-scipy-matplotlib-and-pylab). 

-  In the styles/ directory are a number of files that are customized for the notebook. 
These are not only designed for the book, but they offer many improvements over the 
default settings of matplotlib and the IPython notebook. The in notebook style has not been finalized yet.



Thanks
