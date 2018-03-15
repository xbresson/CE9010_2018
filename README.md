## CE9010: Introduction to Data Science <br> Semester 2 2017/18 <br> Xavier Bresson
  
<br>  
<br>

## Install Python  

For a local installation, it is recommended to install [Miniconda], a distribution of the [conda] package and environment manager. Please follow the below instructions to install it and create an environment for the course:

1. Download the Python 3.6 installer for Windows, macOS, or Linux from <https://conda.io/miniconda.html> and install with default settings. Note for Windows: If you don't know if your operating system is 32-bit or 64-bit, then open Settings-System-About-System type to find out your xx-bit system.
   * Windows: Double-click on the `Miniconda3-latest-MacOSX-x86_64.exe` file. 
   * macOS: Run `bash Miniconda3-latest-MacOSX-x86_64.sh` in your terminal.
   * Linux: Run `bash Miniconda3-latest-Linux-x86_64.sh` in your terminal.
1. Open a terminal. Windows: Open the Anaconda Prompt terminal from the Start menu.
1. Install git: `conda install git`.
1. Download the GitHub repository of the course: `git clone https://github.com/xbresson/CE9010_2018`.
1. Go to folder CE9010_2018 with `cd CE9010_2018`, and create a Python virtual environment with the packages required for the course: `conda env create -f environment.yml`. Note 1: It may take some time. Note 2: List the python packages with `conda list`.

   Note: Instructions based on Michael Defferrard, December 2017<br>
   Note: Useful Conda commands are: `pwd`, `cd`, `ls -al`, `rm -r -f folder/`<br>
   Note: Add a python library to the Python environment: `conda install -n CE9010_2018 numpy` (for example)<br>
   Note: Read [Conda command lines for packages and environments]<br>
   Note: Read [managing Conda environments]

[managing Conda environments]: conda/conda_environments.pdf

[Conda command lines for packages and environments]: conda/conda_cheatsheet.pdf

<br> 






## Run Python notebooks 

First time:

1. Open a terminal. Windows: Open the Anaconda Prompt terminal from the Start menu.
1. Activate the environment. Windows: `activate CE9010_2018`, macOS: `source activate CE9010_2018`.
1. Start Jupyter with `jupyter notebook`. The command opens a new tab in your web browser.
1. Go to the folder `tutorials` and duplicate the original notebook `tutorial01.ipynb` with a new name `my_tutorial01.ipynb` (for example) to avoid future conflicts.
1. Open, edit and run the notebook `my_tutorial01.ipynb` from your browser.
1. When your tutorial is completed, you can go back to the terminal command by shutting down the juypter kernels with `Control-C`. 
1. Save your notebook with git: `git add .`, and `git commit -m tutorial01`.

	Note for Windows: Folder CE9010_2018 is located at `C:\Users\user_name\CE9010_2018`<br>
   Note: Check the status of your git folder: `git status`<br>
   Note: [git commands]<br>
   Note: [Understanding git conflicts]

[git commands]: git/git_commands.pdf
[Understanding git conflicts]: git/git_xb.pdf


<br>
The following times:

1. Open a terminal. Windows: Open the Anaconda Prompt terminal from the Start menu.
1. Activate the environment. Windows: `activate CE9010_2018`, macOS: `source activate CE9010_2018`.
1. Download the new Python notebooks: Go to folder CE9010_2018 with `cd CE9010_2018`, and `git pull`. 
1. Start Jupyter with `jupyter notebook`. The command opens a new tab in your web browser.
1. Go to the folder `tutorials` and duplicate the original notebook `tutorial02.ipynb` with a new name `my_tutorial02.ipynb` (for example) to avoid future conflicts.
1. Open, edit and run the notebook `my_tutorial02.ipynb` from your browser.
1. When your tutorial is completed, you can go back to the terminal by shutting down the juypter kernels with `Control-C`. 
1. Save your notebook with git: `git add .`, and `git commit -m tutorial02`.

<br>




## Run Python notebooks with Binder

&nbsp;&nbsp;&nbsp; dsdsadsadasdsad

&nbsp;&nbsp;&nbsp; No Python installation needed to run the notebooks: Simply [click here]


[Click here]: https://mybinder.org/v2/gh/xbresson/CE9010_2018/master

dsasadasdsad


dsadsadsadsa


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

