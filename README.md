# THEORY-OF-ALGORITHMS
***
![Time Complexity](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6e/Complexity_subsets_pspace.svg/1920px-Complexity_subsets_pspace.svg.png)

# List of contents
***

# What is this repository
***
## This repository contains lab work from my course Theory of Algorithms & my project on the Post Correspondence Problem and the Countdown Numbers Game. These notebooks demonstrate my work on the on explaning the contents and examples of their topics.

![Jupyter notebooks](https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/414px-Jupyter_logo.svg.png)

### This project containts two main [Jupyter notebooks](https://jupyter.org/):
    1.post-correspondence
    2.countdown

### `post-correspondence` explains what the Post Correspondence Problem (PCP) is with examples [PCP](https://en.wikipedia.org/wiki/Post_correspondence_problem#:~:text=One%20of%20the%20most%20important,the%20problem%20is%20NP%2Dcomplete.). In this notebook there is also a Bounded PCP which takes in two lists of strings and checks if they correspond [Bounded PCP](https://cs.stackexchange.com/questions/2783/a-polynomial-reduction-from-any-np-complete-problem-to-bounded-pcp).

### `countdown` covers a [](), []().

# Purpose of this repo:
***
### To demonstrate a deeper understanding of machine learning 

# Files:
***
### There are a few files required for this project in the Github repository

## Lab-work
***
### It contains all previous lab work done in this module that anyone can also glance over to understand the process better and see the development process.

## Docker files 
***
### is a few files 
1. docker-compsoe.yml -> This Compose file defines the service web: The web service uses an image built from the Dockerfile in the current directory. It then binds the container and the host machine to the exposed port, 8888.

2. Dockerfile -> This file builds a `Docker image.` This image contains all the dependencies the Python application requires, including Python itself.

3. requirements.txt -> Contains any packages that need to be brought in through docker to run the notebooks. For these notebooks we dont require any how ever if you want to mess around with quantum computing and machine learning in python you could put `qiskit[visualization].` inside the requirements file and messaround with the notebooks.

## Quick steps
***
### You can view the notebook in dynamic form by clicking the following image:
- post-correspondence

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://github.com/FionnBrowne/THEORY-OF-ALGORITHMS/blob/main/countdown.ipynb)
- countdown

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://github.com/FionnBrowne/THEORY-OF-ALGORITHMS/blob/main/post-correspondence.ipynb)

# Requirements
***
1. [Github](https://github.com/) account .
2. Download [Anaconda](https://docs.anaconda.com/anaconda/install/index.html).
3. Download [cmder](https://cmder.net/) if on Windows.
4. Download [Docker](https://docs.docker.com/get-docker/).
5. Configure your bios to allow WSL2.

# Getting ready.
***
1. Open cmd or the command prompt by going to the Windows search box and typing cmd.
2. In the command prompt/cmd, navigate to your desired location to save the files.
3. Create a file in the selected location by typing in: `$ mkdir fileNameHere`. 
4. Enter this file Ex: type `$ cd Users/NewRepo` for cmd or `$cd Users\NewRepo` for command prompt.
5. Enter the following command to clone the repository: `$ git clone https://github.com/FionnBrowne/Emerging-Technologies.git`

## How to run
***
1. First, navigate to repository location using either cmder or command prompt, for example: `$ cd Users/NewRepo/THEORY-OF-ALGORITHMS`.
2. To run any of the notebooks, type `$ jupyter lab` in the current directory. You also have the option of running the command `$ docker-compose up` to launch it through Docker.

# Possible fixes for issues ???
1. Re-download this repository and make sure your on the right gile.
2. Check in task manager if WSL2 is enabled.
3. Delete the previous files/images and re launch the program.

# Exploring
***
## You could switch out the lists put into the PCP or BPCP calculations or change the K value which is the quantity of tiles that can be used for checking correspondece.

```python
a = 'a'
b = 'b'
L1 = ((a),(a, a),(a, a, a))
L2 = ((b, b, b),(b, b),(b, b))
# 5 being the K value
bpcp_solver(L1, L2, 5) 
```
# Itertools
### `itertools`  [Functions creating iterators for efficient looping](https://docs.python.org/3/library/itertools.html#module-itertools). 

# Learning outcome / conclusion
***



