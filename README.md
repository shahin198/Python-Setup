# Python-Setup
How to setup python

http://docs.python-guide.org/en/latest/starting/installation/

This document describes how to install Python 3.6 on Ubuntu Linux machines.

To see which version of Python 3 you have installed, open a command prompt and run

$ python3 --version

If you are using Ubuntu 16.10 or newer, then you can easily install Python 3.6 with the following commands:

$ sudo apt-get update
$ sudo apt-get install python3.6

If you’re using another version of Ubuntu (e.g. the latest LTS release), we recommend using the deadsnakes PPA to install Python 3.6:

$ sudo apt-get install software-properties-common
$ sudo add-apt-repository ppa:deadsnakes/ppa
$ sudo apt-get update
$ sudo apt-get install python3.6

