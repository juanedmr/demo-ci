[![Python 3.8](https://github.com/juanedmr/demo-ci/actions/workflows/main.yml/badge.svg)](https://github.com/juanedmr/demo-ci/actions/workflows/main.yml)

# demo-ci
Continous integration demo project

----------------------------------------------------
To run this project:

* Create a Github Repo
* Create a virtual environment
* Pair both with an SSH key
* Upload the SSh key to Github
* Run the makefile project with the proper configuration:

The file contains the following configurations for the venv:

```
install:
	pip install --upgrade pip &&\
		pip install -r requirements.txt

install-gcp:
	pip install --upgrade pip &&\
		pip install -r requirements-gcp.txt

install-aws:
	pip install --upgrade pip &&\
		pip install -r requirements-aws.txt

install-amazon-linux:
	pip install --upgrade pip &&\
		pip install -r amazon-linux.txt

```

Run `make ___` according to your venv


[Demo video in AWS for this project](https://www.youtube.com/watch?v=p3yDxVSr2Ms)
