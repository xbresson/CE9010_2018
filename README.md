## CE9010: Introduction to Data Science <br> Semester 2 2017/18 <br> Xavier Bresson
    
<br>    
<br>


## Slides of the course
<br>


[Lecture 1: Introduction]

[Lecture 2: Learning Techniques]

[Lecture 3: Supervised Linear Regression]

[Lecture 4: Supervised Classification]

[Lecture 5: Gradient Descent Tricks]

[Lecture 6: Generalization and Regularization]

[Lecture 7: Developing Data Science Projects]

[Lecture 8: Unsupervised Learning]

[Lecture 9: Recommender Systems]

[Lecture 10: Neural Networks]


[Lecture 1: Introduction]: slides/CE9010_lecture01_intro.pdf
[Lecture 2: Learning Techniques]: slides/CE9010_lecture02_learning_techniques.pdf
[Lecture 3: Supervised Linear Regression]: slides/CE9010_lecture03_supervised_regression.pdf
[Lecture 4: Supervised Classification]: slides/CE9010_lecture04_supervised_classification.pdf
[Lecture 5: Gradient Descent Tricks]: slides/CE9010_lecture05_gradient_descent_tricks.pdf
[Lecture 6: Generalization and Regularization]: slides/CE9010_lecture06_generalization_and_regularization.pdf
[Lecture 7: Developing Data Science Projects]: slides/CE9010_lecture07_developing_data_science_projects.pdf
[Lecture 8: Unsupervised Learning]: slides/CE9010_lecture08_unsupervised_learning.pdf
[Lecture 9: Recommender Systems]: slides/CE9010_lecture09_recommender_systems.pdf
[Lecture 10: Neural Networks]: slides/CE9010_lecture10_neural_networks.pdf




<br>
<br>

## Python notebooks of the course
<br>

[Tutorial 1: Introduction to Python]

[Tutorial 2: Linear algebra in Python]

[Tutorial 2: Linear algebra in Python - solution]

[Tutorial 3: Linear supervised regression]

[Tutorial 3: Linear supervised regression - solution]

[Tutorial 4: Supervised classification]

[Tutorial 4: Supervised classification - solution]

[Tutorial 5: Polynomial supervised classification]

[Tutorial 5: Polynomial supervised classification - solution]

[Tutorial 6: Bias vs. variance]

[Tutorial 6: Bias vs. variance - solution]

[Tutorial 7: PCA]

[Tutorial 7: PCA - solution]

[Tutorial 8: Neural networks]

[Tutorial 8: Neural networks - solution]



[Tutorial 1: Introduction to Python]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial01.ipynb
[Tutorial 2: Linear algebra in Python]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial02.ipynb
[Tutorial 2: Linear algebra in Python - solution]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial02_solution.ipynb
[Tutorial 3: Linear supervised regression]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial03.ipynb
[Tutorial 3: Linear supervised regression - solution]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial03_solution.ipynb
[Tutorial 4: Supervised classification]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial04.ipynb
[Tutorial 4: Supervised classification - solution]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial04_solution.ipynb
[Tutorial 5: Polynomial supervised classification]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial05.ipynb
[Tutorial 5: Polynomial supervised classification - solution]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial05_solution.ipynb
[Tutorial 6: Bias vs. variance]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial06.ipynb
[Tutorial 6: Bias vs. variance - solution]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial06_solution.ipynb
[Tutorial 7: PCA]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial07.ipynb
[Tutorial 7: PCA - solution]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial07_solution.ipynb
[Tutorial 8: Neural networks]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial08.ipynb
[Tutorial 8: Neural networks - solution]: https://github.com/xbresson/CE9010_2018/blob/master/tutorials/tutorial08_solution.ipynb





<br>
<br>
## Running Python notebooks without local Python installation
<br>

&nbsp;&nbsp;&nbsp; Run the notebooks from the cloud using Binder: Simply [click here].

[Click here]: https://mybinder.org/v2/gh/xbresson/CE9010_2018/master





<br>
<br>
## Local Python installation
<br>

Follow the following instructions to install Miniconda and create a Python environment for the course:

1. Download the Python 3.6 installer for Windows, macOS, or Linux from <https://conda.io/miniconda.html> and install with default settings. Note for Windows: If you don't know if your operating system is 32-bit or 64-bit, then open Settings-System-About-System type to find out your xx-bit system.
   * Windows: Double-click on the `Miniconda3-latest-MacOSX-x86_64.exe` file. 
   * macOS: Run `bash Miniconda3-latest-MacOSX-x86_64.sh` in your terminal.
   * Linux: Run `bash Miniconda3-latest-Linux-x86_64.sh` in your terminal.
1. Windows: Open the Anaconda Prompt terminal from the Start menu. MacOS, Linux: Open a terminal.
1. Install git: `conda install git`.
1. Download the GitHub repository of the course: `git clone https://github.com/xbresson/CE9010_2018`.
1. Go to folder CE9010_2018 with `cd CE9010_2018`, and create a Python virtual environment with the packages required for the course: `conda env create -f environment.yml`. Note that the environment installation may take some time. 
   
   Notes: <br>
      The installed conda packages can be listed with `conda list`.<br>
      Some useful Conda commands are `pwd`, `cd`, `ls -al`, `rm -r -f folder/`<br>
      Add a python library to the Python environment: `conda install -n CE9010_2018 numpy` (for example)<br>
      Read [Conda command lines for packages and environments]<br>
      Read [managing Conda environments]

[managing Conda environments]: conda/conda_environments.pdf

[Conda command lines for packages and environments]: conda/conda_cheatsheet.pdf





<br> 
## Running local Python notebooks 
<br>

First time:

1. Windows: Open the Anaconda Prompt terminal from the Start menu. MacOS, Linux: Open a terminal.
1. Activate the environment. Windows: `activate CE9010_2018`, macOS, Linux: `source activate CE9010_2018`.
1. Start Jupyter with `jupyter notebook`. The command opens a new tab in your web browser.
1. Go to the folder `tutorials` and duplicate the original notebook `tutorial01.ipynb` with a new name `my_tutorial01.ipynb` (for example) to avoid future conflicts, see [understanding git conflicts].
1. Open, edit and run the notebook `my_tutorial01.ipynb` from your browser.
1. When your tutorial is completed, you can go back to the terminal command by shutting down the juypter kernels with `Control-C`. 
1. Save your notebook with git: `git add .`, and `git commit -m tutorial01`.

	Notes:<br> 
      Windows: Folder CE9010_2018 is located at `C:\Users\user_name\CE9010_2018`. MacOS, Linux: `/Users/user_name/CE9010_2018`.<br>
      Check the status of your git folder: `git status`<br>
      List of [git commands]<br>
      Windows systems may print the `warning: LF will be replaced by CRLF` when git commit. You can deactivate this warning with `git config core.autocrlf false`.


[git commands]: git/git_commands.pdf
[understanding git conflicts]: git/git_xb.pdf


<br>
The next times:

1. Windows: Open the Anaconda Prompt terminal from the Start menu. MacOS, Linux: Open a terminal.
1. Activate the environment. Windows: `activate CE9010_2018`, macOS, Linux: `source activate CE9010_2018`.
1. Download the new Python notebooks: Go to folder CE9010_2018 with `cd CE9010_2018`, and `git pull`. 
1. Start Jupyter with `jupyter notebook`. The command opens a new tab in your web browser.
1. Go to the folder `tutorials` and duplicate the original notebook `tutorial02.ipynb` with a new name `my_tutorial02.ipynb` (for example) to avoid future conflicts, see [understanding git conflicts].
1. Open, edit and run the notebook `my_tutorial02.ipynb` from your browser.
1. When your tutorial is completed, you can go back to the terminal by shutting down the juypter kernels with `Control-C`. 
1. Save your notebook with git: `git add .`, and `git commit -m tutorial02`.




<br>
Clean re-installation of the GitHub repository: 

1. For GitHub beginners who wish to re-start from a clean GitHub repository of the course. 
1. Backup the current folder by changing the folder name `CE9010_2018` to `CE9010_2018_backup` (for example).
1. Re-download the GitHub repository of the course: `git clone https://github.com/xbresson/CE9010_2018`.
1. Copy-paste your own notebooks from `CE9010_2018_backup/tutorials` to the new folder `CE9010_2018/tutorials`.
1. Follow instructions `The next times`.









[git]: https://git-scm.com
[python]: https://www.python.org
[scipy]: https://www.scipy.org
[anaconda]: https://anaconda.org
[miniconda]: https://conda.io/miniconda.html
[conda]: https://conda.io
[conda-forge]: https://conda-forge.org


<br>
<br>
<br>
<br>
<br>
<br>



