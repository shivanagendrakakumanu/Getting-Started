# Getting started

This repo is just to get you ready to move onto more interesting stuff.

It covers:
- Getting started with your terminal (command line interface (CLI))
- Setting up your python package manager (your package manager that allows you to use useful python code that others have written)
- Setting up Python 3 (the latest version of the Python programming language)
- Setting up PyTorch (our deep learning framework library)
- Setting up Jupyter Notebook

### Struggling?
- ask google (I do this about 100 times per day)
- Look on YouTube for tutorials 
- [Book office hours](https://theaicore.com/app) by logging into our webapp for help if you get really stuck
- Come along 30 minutes early to one of our next sessions.

### Recommendations
- Use Linux instead of Windows or MacOS. It will be a steep learning curve but worth it long term if you want to be an AI deveoper.
- Use [VS Code](https://code.visualstudio.com/download) as your editor (where you write code) when you want to write code to deploy
- Use pip as your package manager. Conda is not recommended - we can provide less support for it, because we don't use it.

You should move on once you can successfully run `import torch` in a jupyter notebook. If you don't know what any of the above means, or can't run that command in a jupyter notebook, then follow the steps below.

## 1. Using the terminal
The terminal lets you interact with your operating system. You can type in commands to make your computer do pretty much anything. It's not designed to be pretty,  it has no graphical user interface (GUI). It will run a language called bash, which I introduce [here](https://github.com/life-efficient/Academy-of-AI/blob/master/theCLI.ipynb). We will use it in the following steps.

### Linux 
Open the terminal by searching for terminal or by **pressing CTRL+ALT+T** (learn this)

### Mac
Search for terminal and open it

### Windows
Download Anaconda from [here](https://www.anaconda.com/distribution/#download-section)

## 2. Setting up your package manager

A package manager allows you to install useful code (packages/libraries) that others have written. Pip is a package manager for Python code.

We will be using Python 3, so we need to install packages that are written in Python 3. Many libraries are available in both Python 2 and 3. pip2 installs Python 2 packages and pip3 installs Python 3 packages.

We will install pip**3** which is for Python 3, not pip2 which is for Python 2 (you can also use brew if you're on Mac, but we will be able to help each other more easily if we all use the same tools)

You can install packages using pip by running `pip install insert_package_name_here`

Type `pip -V` in your terminal and press enter to tell your terminal to let you know what version of pip you have. It should return you a line which tells you which version of Python this is for. If it doesnt say python3.x (where x is any number) then try run `pip3 -V`. You may need to install pip3, so run `sudo apt install pip3` (**sudo means 'super user do' and it executes the command with ALL priveleges. Be careful not to destroy your computer by using it recklessly. When you run it, it will ask for your password - but it will not show you the password when it's being typed**) in your terminal and then try run `pip3 -V` again. If `pip3 -V` tells you that it's for Python 3 but `pip2 -V` doesn't, then you will need to install packages with the `pip3` command rather than the `pip` command e.g. `pip3 install insert_package_name_here`. It may be helpful to use an *alias* to map the `pip` command to `pip3`, check out [this](https://github.com/life-efficient/Academy-of-AI/blob/master/theCLI.ipynb) repo to see how to do that.

### MacOS
[This](https://www.youtube.com/watch?v=W3k8_8ahsyg) guide looks pretty useful

### Linux
You're good.

## 3. Running Python 3

Run `python` in your terminal. The prompt (start of line) should change to indicate that you are now running python, not bash (terminal language). On the first line below it should tell you the version you are using. If it's not >3.0 then run `python3` (again here you could use an alias to make it so that `python3` is run when you run `python`. 

Note that if you run `python` then your prompt will change (probably from `$` to `>>>`). This indicates that you are running python inside your terminal. You will need to exit python by pressing `CTRL+d` to return to your terminal before trying to run any further terminal commands like `python3`.

## 4. Setting up PyTorch

Go to [the PyTorch website](https://pytorch.org/get-started/locally/) and select the relevant options. This will show you a bash command. Copy it and run it in your terminal.

## 5. Setting up Jupyter Notebook
Run `sudo pip3 install notebook` in your terminal. Now run `jupyter-notebook` (make an alias maybe).

Check out [this](https://www.youtube.com/watch?v=jZ952vChhuI) video to understand jupyter notebook.

### If you can run `import torch` in a jupyter-notebook cell, then you've completed the setup! 

### Run through the [intro-to-python.ipynb](https://github.com/AI-core/basic-python) by downloading that repo, running `jupyter-notebook` in your terminal and then navigating to where it is located and opening it. 

### If you're already familiar with python then move on and check out:
- [basic data science](https://github.com/AI-core/basic-data-science/blob/master/README.md)
- [using git and github](https://github.com/life-efficient/Academy-of-AI/blob/master/Git%20and%20GitHub.ipynb)
- [using the command line interface](https://github.com/life-efficient/Academy-of-AI/blob/master/theCLI.ipynb)

### If that didn't work
SUPER EASY SETUP WITH A VIRTUAL MACHINE: follow [this guide](https://github.com/AI-Core/Getting-Started/blob/master/Setting%20up%20a%20Virtual%20Machine%20(VM).md) to set up a virtual machine. Definitely do this if you use windows.

If you want to set up your environment without a virtual machine
