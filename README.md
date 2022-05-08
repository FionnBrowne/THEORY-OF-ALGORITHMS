# THEORY-OF-ALGORITHMS
***

![Computational theory](https://onlinelibrary.wiley.com/cms/asset/1434d5f7-bbf1-4267-a483-d30807979c22/cogs12012_f1.gif)

# List of contents
***
1. [Purpose of repository](#purpose-of-repository)
2. [Expected Learning outcomes](#expected-learning-outcomes)
3. [Files](#files)
    - [Lab work](##lab-work)
    - [Docker files](##docker-files)
4. [Quick steps](#quick-steps)
5. [Requirements](#requirements)
6. [Getting ready](#getting-ready)
    - [How to run](##how-to-run)
    - [Possible fixes for issues ???](##possible-fixes-for-issues-???)
7. [Exploring](#exploring)
8. [Itertools](#itertools)


# Purpose of repository
***
## This repository contains lab work from my course [`Theory of Algorithms`](https://learnonline.gmit.ie/course/view.php?id=5197), my project work on the [`Post Correspondence Problem`](https://github.com/FionnBrowne/THEORY-OF-ALGORITHMS/blob/main/post-correspondence.ipynb)(PCP) and the [`Countdown Numbers Game`](https://github.com/FionnBrowne/THEORY-OF-ALGORITHMS/blob/main/countdown.ipynb) using Python libraries. The [`Jupyter notebooks`](https://jupyter.org/) demonstrate my work on explaining the contents and examples of their topics (Post-Corrspondence and Countdown).  
- Some of the tools used in the PCP notebook are [`Sets`](https://docs.python.org/3/tutorial/datastructures.html#sets), [`Tuples`](https://docs.python.org/3/tutorial/datastructures.html#tuples-and-sequences) and [`Itertools`](https://realpython.com/python-itertools/). These Libraries are provided by Python, which are used to explain what the PCP is and show an example of PCP and also a modified version, called bounded PCP.
- The [`Countdown`](https://github.com/FionnBrowne/THEORY-OF-ALGORITHMS/blob/main/countdown.ipynb) notebook gives an overview of the British TV game show, shows how complex the numbers section of the show is and a Python function to solve it.

![Jupyter notebooks](https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/414px-Jupyter_logo.svg.png)

### This project containts two main [Jupyter notebooks](https://jupyter.org/):
    1.Post-correspondence
    2.Countdown

### `Post-correspondence` explains what the Post Correspondence Problem (PCP) is with examples [PCP](https://en.wikipedia.org/wiki/Post_correspondence_problem#:~:text=One%20of%20the%20most%20important,the%20problem%20is%20NP%2Dcomplete.). In this notebook there is also a Bounded PCP which takes in two lists of strings and checks if they correspond [Bounded PCP](https://cs.stackexchange.com/questions/2783/a-polynomial-reduction-from-any-np-complete-problem-to-bounded-pcp).

### `Countdown` covers a British [`game show`](https://en.wikipedia.org/wiki/Countdown_(game_show)), where the game rules are explained, and then the complexity of the numbers section is considered. Then there is a function to solve the countdown game, this takes in a list of six numbers and a target number and then returns a method to calculate the target from the numbers, if it exists.

# Expected Learning outcomes
***
### To demonstrate a deeper understanding of computational complexity.
- Compare different models of computation.
- Write computer programmes using a selection of programming paradigms.
- Analyse the complexity of an algorithm.
- Identify difficult computational problems in everyday programming.

# Files:
***
### There are a several files required for this project in the Github repository, the main files being explained below. 

## Lab work file
***
### It contains all previous lab work carried out in this module. It can be used for quick reference and helps to understand the development process better. 

## Docker files 
***
### Docker overview 
1. docker-compsoe.yml -> This compose file defines the service web: The web service uses an image built from the Dockerfile in the current directory. It then binds the container and the host machine to the exposed port, 8888.

2. Dockerfile -> This file builds a `Docker image.` This image contains all the dependencies that the Python application requires, including Python itself.

3. requirements.txt -> Contains any packages that need to be brought in through docker to run the notebooks. For these notebooks we dont require any, however if you wanted to experiment with quantum computing and machine learning in python you could put `qiskit[visualization].` inside the requirements file and work with the notebooks.

# Quick steps
***
### You can view the notebook in dynamic form by clicking the following image:
- Post-correspondence
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://github.com/FionnBrowne/THEORY-OF-ALGORITHMS/blob/main/post-correspondence.ipynb)

- Countdown
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://github.com/FionnBrowne/THEORY-OF-ALGORITHMS/blob/main/countdown.ipynb)


# Requirements
***
1. [Github](https://github.com/) account .
2. Download [Anaconda](https://docs.anaconda.com/anaconda/install/index.html).
3. Download [cmder](https://cmder.net/) if on Windows.
4. Download [Docker](https://docs.docker.com/get-docker/).
5. Configure your bios to allow WSL2.

# Getting ready
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

## Possible fixes for issues 
1. Re-download this repository and make sure you are on the right file.
2. Check in task manager if WSL2 is enabled.
3. Delete the previous files/images and re launch the programme.

# Exploring
***
## You could switch out the lists put into the PCP or BPCP calculations or change the K value which is the quantity of tiles that can be used for checking correspondence.

```python
a = 'a'
b = 'b'
L1 = ((a),(a, a),(a, a, a))
L2 = ((b, b, b),(b, b),(b, b))
# 5 being the K value
bpcp_solver(L1, L2, 5) 
```
# Itertools
### `itertools` is a module that [incorporates functions, utilising computational resources efficiently](https://docs.python.org/3/library/itertools.html#module-itertools). It is used to iterate over data structures that can be stepped over using a for-loop.
