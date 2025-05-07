$ conda env create -f dependencies.yml<br>
$ conda activate gpu-basics

---------
$ conda create -n macenv python=3.11 -y
$ conda activate macenv
$ pip install ipykernel notebook ipython==8.10.0
$ pip install tensorflow-macos==2.13.0 tensorflow-recommenders==0.7.3
$ pip install "typing-extensions<4.6.0,>=3.6.6" --force-reinstall
$ python -m ipykernel install --user --name tfmacenv --display-name "Python (tfmac)"
