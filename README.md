# Statistical Rethinking Exercise Solutions
In this repository we collect the solutions (so far done) to the exercises which are provided
in the book "Statistical Rethinking---A Bayesian Course with Examples in R and Stan." The website,
which goes with this book, can be found [here](http://xcelab.net/rm/statistical-rethinking/).
Furthermore, the author of the book, [Richard McElreath](https://xcelab.net/rm/), presented the
content of the book also as lecture of which the records can be found on
[YouTube](https://www.youtube.com/playlist?list=PLDcUM9US4XdNM4Edgs7weiyIguLSToZRI).


Contrary to the book title, we solved the problems by means of [Pyro](http://pyro.ai/). Getting
ourselves familiarised with Pyro was also the main intention behind working out all these examples
explicitly.


## Solutions

The solutions for each chapter are provided in one jupyter notebook which can be found here:

* [Solutions Chapter 2](<notebooks/Practice Chapter 2.ipynb>)
* [Solutions Chapter 3](<notebooks/Practice Chapter 3.ipynb>)
* [Solutions Chapter 4](<notebooks/Practice Chapter 4.ipynb>)
* [Solutions Chapter 5](<notebooks/Practice Chapter 5.ipynb>)
* ...


## Getting started

To have a working environment to run the code provided in this repository, please use our docker file
and docker compose file. For instance, to obtain a jupyter server including a working python kernel,
please run

    $docker-compose up devboxjupyter

and follow the link provided in the shell.
