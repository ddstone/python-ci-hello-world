# python-ci-hello-world

A python continuous integration hello world
Use _Github_ as hosting server and CircleCI as our external CI service;

## Step

0. Set up an clean python environment.

1. Set up a repository and commit the code.

2. Write Unit Tests.

	Adding tests to make sure your code works the way it's supposed to.
	
	A unit test is designed to check a single function, or unit, of code.
	
	A standard practice that goes hand in hand with testing is calculating code coverage -- The percentage of source code that is "covered" by your test;
	
	Use `pytest-cov`, an extension of `pytest`;
	
	- Make sure to store those dependencies in a `requirements.txt` file so others can replicate your environment;

