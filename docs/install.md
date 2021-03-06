# Installation

In order to install MkDocs you'll need Python installed on your system, as well as the Python package manager, pip. You can check if you have these already installed like so:
```
$ python --version
Python 2.7.2
$ pip --version
pip 1.5.2
```
Opinator supports Python 2.6, 2.7.

## Download Project

Download the [Opinator Server project](https://github.com/vivekanand1101/opinator-coreserver) from Github.

You can also use git to clone the repo to your local system using:

```
$ git clone https://github.com/vivekanand1101/opinator-coreserver.git
$ cd opinator2
```

## Install Dependencies

Run the following codes to install all dependencies:
```
$ ./install.sh
$ sudo pip install -r requirements.txt
$ sudo python setup.py
```

You need to download [nltk_data](https://drive.google.com/open?id=0B61cpCJqkzqveFhsOTdVSVZwb1E) and [stanford corenlp package](https://drive.google.com/open?id=0B61cpCJqkzqvVi1RNFNYLWVXTG8):

You can also download nltk_data as follow:
```
$ python
> import nltk
> nltk.download()
```

