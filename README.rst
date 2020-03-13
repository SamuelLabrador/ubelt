# DEPENDENCIES

## Python Version

python == 3.7.5

## PIP Packages

attrs==19.3.0
certifi==2019.11.28
chardet==3.0.4
codecov==2.0.16
coverage==5.0.3
idna==2.9
importlib-metadata==1.5.0
more-itertools==8.2.0
mutatest==3.0.0
numpy==1.18.1
ordered-set==3.1.1
packaging==20.3
pluggy==0.13.1
py==1.8.1
Pygments==2.6.1
pyparsing==2.4.6
pytest==5.3.5
pytest-cov==2.8.1
requests==2.23.0
six==1.14.0
typing-extensions==3.7.4.1
-e git+https://github.com/SamuelLabrador/ubelt.git@3cdf7b80c7716c263b4eb8be448371589dc8f174#egg=ubelt
urllib3==1.25.8
wcwidth==0.1.8
xdoctest==0.11.0
xxhash==1.4.3
zipp==3.1.0

## Setup

1. Ensure that the exact version of python is installed as sepecified above, otherwise the mutation tests will not run.

2. Within the root project directory run "python -m pip install -r requirements.txt"

3. Run "mutatest -r {SEED}". Mutatest only runs a random selection of mutations. Entering a {SEED} value of 1 will ensure that you can run the same mutants again. For this project we ran seeds: {1, 2, 3, 4, 5, 6}
