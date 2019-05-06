### Install with anaconda

To install the code in your computer, you need first to install the anaconda
python (https://www.anaconda.com/download).

**You will have to use the Python 3.x distribution.**

It is a good practice to update all your installed packages to have the latest versions:

conda update --all -y

The packages *lmfit* and *reproject* have to be installed from the astropy channel:

conda install -c astropy lmfit -y

conda install -c astropy reproject -y

Now you are ready to install sospex:

conda install -c darioflute sospex -y

### Updating with anaconda

If there is a new release, you will have only to update the package:

conda update -c darioflute sospex -y

Alternatively, add the channel to your anaconda:

conda config --add channels darioflute

and simply do:

conda update sospex

### Install with pipy

pip install sospex

to update:

pip install --upgrade sospex