# Numpy.Random Package Analysis
This assignment has been completed in accordance with the tasks set out in the coursework of the Programming for Data Analysis module as part of the Higher Diploma in Data Analytics in Galway-Mayo Institute of Technology.

## Assignment completed by:
Declan Reidy - November 2018

## Instructions

In order to complete this assigment it was necessary to:
1. Download & install Anaconda
2. Download & install Console Emulator x64
3. Create directory and files such as this README, LICENSE and .gitignore using Linux commands
4. Launch a jupyter notebook from the command line and create Numpy-Random.ipynb
5. Sync files on my local machine to repository on GitHub allow me to push/pull updates to the jupyter notebook over various commits

To review the analysis methods and conclusions from the assigment:
1. Simply launch the Jupyter Notebook entitled "Numpy-Random.ipynb"
2. Review the full analysis in the Jupyter Notebook
3. Run individual elements of the python code by highlighting cells and using command SHIFT+ENTER
4. Consult the "Initial Research" section of this README file for information on my approach this assignment
5. Consult the "Method" section of this README file for information on my methodology this assignment
6. Consult the "References & Research" section of this README file for finformation on my further reading in relation to this assigment

## Initial Research
From the lecture series and background material in the course throughout the opening 8 weeks it was clear that the assignment was likely to build on various aspects of the coursework introduced during the lecture series.

Much of our learning from the different libraries such as Python, Matplotlib, Numpy, Pandas, Sklearn, Jupyter has lent itself to a lot of investigation over the semester and simulating elements of various packages. That the assignment requested us to investigate a particular package indepth only cemented the idea of how much trial, error and discovery is required to develop our programming skills as (relative) beginners.

Initial research of the the Numpy.random package points us to the generation of random numbers and the applications of such concepts in the real world. Aspects such as seeds are called out directly in the assigment and as such formed the basis of my intial searches and provides the explanation for my choice of resources below.

## Method
Given the initial research, I quickly settled on an approach that would try to apply the learnings of numpy.random to real world applications where possible. I have focused on the generation of pseudorandom numbers using the numpy.random package as well as 5 distributions in addition to the specific requirements to provide descriptions and examples of the "Simple random data" and "Permutations functions"

The approach therefore became about demonstrating using the numpy.random library:
1. Rand() function
2. Randn() function
3. Random-sample() function
4. Permutation() function
5. Standard_normal() distribution
6. Uniform() distribution
7. Poisson() distribution
8. Rayleigh() distribution
9. Geometric() distribution
10. Seed() function


## References & Research
https://docs.scipy.org/doc/numpy-1.15.0/
Numpy.random documentation

https://www.packtpub.com/mapt/book/big_data_and_business_intelligence/9781785285110/2/ch02lvl1sec16/numpy-random-numbers
Generation of random numbers important to any simulation. Numpy.Random produces pseudorandom numbers using an algorithm called Mersenne Twister. Random.Random does the same in Python. Key differences are range of applications and more efficient mathematical operations.

You can define a seed to start or initialise the generation of a  random number. This is basically how tokenisation works.

https://www.bbc.com/news/technology-33839925

There are shortcomings in the generation of random numbers used to encrypt or scramble data.
Data needs to have a high entropy to be useful for random numbers. High entropy means higher disorder. Low entropy means more predictable. Generally generated from the state of the computer system (time is the obvious one)

Pseudorandom - exhibiting statistical randomness while being generated by entirely deterministic causal process.  This process is easier to produce than a genuinely random one and can be used again and again to produce exactly the same numbers.

This process often involves storing keystrokes, I/O movements, voltage measurements to produce a pool, and a seed is then formed from this pool. The pool is constantly replenished.

https://www.rand.org/pubs/monograph_reports/MR1418/index2.html

Historically this was done using dice, cards or roulette wheels

https://machinelearningmastery.com/how-to-generate-random-numbers-in-python/

Pseudorandomness is a sample of numbers that look close to random, but were generated using a deterministic process.

Shuffling data and initializing coefficients with random values use pseudorandom number generators. These little programs are often a function that you can call that will return a random number. Called again, they will return a new random number. Wrapper functions are often also available and allow you to get your randomness as an integer, floating point, within a specific distribution, within a specific range, and so on.

The numbers are generated in a sequence. The sequence is deterministic and is seeded with an initial number. If you do not explicitly seed the pseudorandom number generator, then it may use the current system time in seconds or milliseconds as the seed. The value of the seed does not matter. Choose anything you wish. What does matter is that the same seeding of the process will result in the same sequence of random numbers.
