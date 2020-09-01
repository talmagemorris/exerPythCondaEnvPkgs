# Setting up Environments and Installing Packages Using Conda

## Summary of steps to complete

- [ ] Fork this repository so you have your own copy to work on.
- [ ] Clone the repository on your local machine. 
- [ ] Edit this README.md file on your machine.
- [ ] Run the Conda commands shown in the video and describe them in the table below.
- [ ] Push your changes to your GitHub repository.
- [ ] Submit a link to this GitHub repository in Canvas.

## 1. Fork & Clone this repository

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/N6806_Fall2020_DevNotes/blob/master/Projects/002%20-%20Practice%20Using%20Git%20and%20GitHub/README.md
* This can also be done directly in VSCode
  * Create a new folder on your machine where you want to put this repository if you don't already have one you want to use.
  * Copy the Clone or Download path for this repository from GitHub.
  * In VSCode from the command pallette (Ctrl-Shift-P) run Git: Clone
  * Paste the path into the path field which pops up
  * Select your new folder you created on your machine
  * A new folder for the repository with the repository files should be in the folder you selected showing in the Explorer window in VSCode on the left side.
  
## Edit your README.md file

* [ ] In an editor of your choice (i.e. VSCode) edit this README.md file to add the answers requested in the tables.

## Follow along with this tutorial

* Conda What and Why? (27 min): https://www.youtube.com/watch?v=23aQdrS58e0&list=PLG9A6ovzPqX6d9uWzx0UYN9pm0zzl5ofA&index=13&t=0s
  * He installs Miniconda. We will be using Anaconda. Don't install Miniconda.
  * Follow along with the rest of the tutorial.
  * Go ahead and create the environments as he creates them in the tutorial.

## Conda Concepts

* [ ] Describe the Conda concepts used in the video and listed in the table below.

|   Concept   |         Description or short answer         |
|     ---     |                     ---                     |
|What is the purpose of having different environments?     |(To be able to format different enviornments for specific goals without haveing multiple computers)|
|What is the default package manager in Python?            |(pip)|
|How do you manage environments and packages in Anaconda?  |(conda activate (env name or conda install numpy ))|
|`conda list`       |(# Name                    Version                   Build  Channel
blas                      1.0                         mkl
ca-certificates           2020.7.22                     0
certifi                   2020.6.20                py38_0
intel-openmp              2020.2                      254
mkl                       2020.2                      256
mkl-service               2.3.0            py38hb782905_0
mkl_fft                   1.1.0            py38h45dec08_0
mkl_random                1.1.1            py38h47e9c7a_0
numpy                     1.19.1           py38h5510c5b_0
numpy-base                1.19.1           py38ha3acd2a_0
openssl                   1.1.1g               he774522_1
pip                       20.2.2                   py38_0
python                    3.8.5                he1778fa_0
setuptools                49.6.0                   py38_0
six                       1.15.0                     py_0
sqlite                    3.33.0               h2a8f88b_0
vc                        14.1                 h0510ff6_4
vs2015_runtime            14.16.27012          hf0eaf9b_3
wheel                     0.35.1                     py_0
wincertstore              0.2                      py38_0
zlib                      1.2.11               h62dcd97_4)|
|`conda env list`       |((da35) C:\Users\talma>conda env list
# conda environments:
#
base                     C:\Users\talma\anaconda3
ai37                     C:\Users\talma\anaconda3\envs\ai37
da35                  *  C:\Users\talma\anaconda3\envs\da35)|
|How do you keep your base environment unchanged?       |(enter description or short answer here)|
|What is the link to the Conda cheat sheet? (link in video notes is broken)      |(https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)|
|`conda create --name XXXX`       |(creates an enviornment)|
|`source activate XXXX`       |(switches between enviornments)|
|`conda install YYYY`       |(installs packages)|
|channels in Conda       |(locations where packages are stored)|
|`conda install -c ZZZZ YYYY`       |(install a package through a specific channel)|
|`conda config --show channels`       |(Shows a list of channels)|
|`conda config --add channels ZZZZ`       |(adds a channel to the env you are in)|
|conda-forge.org       |(enter description or short answer here)|
|`source deactivate`       |(deactivate current env)|
|`conda config --get channels`       |(enter description or short answer here)|

* After creating the environments he created in the video on your computer, what would the results of running the command `conda env list` look like with the da35 environment activated. Paste the output from your command prompt in the code block below.

```
#Paste your results here.
base                  *  C:\Users\talma\anaconda3
ai37                     C:\Users\talma\anaconda3\envs\ai37
da35                     C:\Users\talma\anaconda3\envs\da35

```
* What command would you use to remove the environments you created for this exercise from your computer?

```
#Type the command here.
conda env remove --name myenv
```

