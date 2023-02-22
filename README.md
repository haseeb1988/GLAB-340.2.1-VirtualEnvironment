# Guided Lab - Virtual Environments in Python


## Introduction

Create Virtual Environment for venv, virtualenv and conda

## Lab Overview
In this lab, we'll create virtual environment for venv, virtualenv and conda

## Examples
## Example 1: How to create and activate a virtual environment in Python using venv module
Sure, here's an example of how to create and activate a virtual environment in Python using venv module:

First, open your command prompt or terminal and navigate to the directory where you want to create the virtual environment.

Next, create a new virtual environment by running the following command:

```
python -m venv myenv
```

This will create a new directory named myenv that contains the virtual environment.

Activate the virtual environment by running the appropriate command for your operating system:

On Windows:

```
myenv\Scripts\activate
```
On Linux or macOS:
```
source myenv/bin/activate
```
This will activate the virtual environment and you will see its name displayed in your command prompt or terminal.

You can now install any required packages or dependencies within this virtual environment using pip. For example:

```
pip install pandas
```

## Example 2: 
