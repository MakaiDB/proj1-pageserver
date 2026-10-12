# README

A "getting started" project for CIS 322, introduction to software engineering, at the University of Oregon.

### What is this repository for?

The objectives of this mini-project are:

* Experience with GIT workflow with separate configuration: Fork the project, make and test changes locally, commit; turn in configuration file with reference to repo. (Project 0 is practice for this part.) 
* Extend a tiny web server in Python, to check understanding of basic web architecture
* Use automated tests to check progress (plus manual tests for good measure)

### What do I need?  Where will it work?
 "* Designed for Unix, mostly interoperable on Linux (Ubuntu) or MacOS. May also work on Windows, but no promises. A Linux virtual machine may work, but our experience has not been good; you may want to test on shared server ix-dev.

* You will need Python version 3.4 or higher.

* Designed to work in "user mode" (unprivileged), therefore using a port number above 1000 (rather than port 80 that a privileged web server would use)

### testing

* Make and test your changes. Use both automated tests (the script in the 'tests' directory) and some manual tests.
  
* Test deployment in other environments. Deployment should work "out of the box" with this command sequence: 

  ```
  git clone <yourGitRepository> <targetDirectory>
  ```
  
  ```
  cd <targetDirectory>
  ```
  
  ```
  make run or make start
  ```
  
  *test it with a browser now, while your server is running in a background process*

  ```
  make stop
  ```
  
* Alternatively, use the script under "tests" folder to test the expected outcomes in an automated fashion. It is accompanied by README file and comments (inside `tests.sh`) explaining how to test your code.