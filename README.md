# Edges detection of an image using Numpy, PIL, Math and Requests packages

[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)

One simple program using `Python` for detecting edges.<br>
The following gist offers a program scaled in seven parts:
1. Import `Numpy` and related packages
2. Load image remotely and define scaling variables
3. Create output image
4. Convert image to grayscale
5. Compute intensity convolution using a for `loop`
6. Draw magnitude in black and white
7. Print out input and output images

## Getting Started

This `Python` program built in 21 lines helps you render edges from a given image.
The below instructions will help you run this Python program on your local machine for development and testing purposes, as well as in third party sites hosted in the cloud.
* (#) and (''') are used to comment the following gist.

### Prerequisites

I am using `Jupyter` Notebook on localhost (Ubuntu 18.04 bionic).<br>
You can use `Python` IDEs and code editors on remote servers (see Tips).

### Tips

If you are not using Linux/Unix and still want to try this simple Python program:
* use https://www.cloud9.gg/ (recommended if you are an historic Cloud9 user)
* use https://colab.research.google.com/ (recommended if you have a Gmail account)
* use https://dataplatform.ibm.com (recommended for IBM Coders)
* you may not want to use `Pycharm` to avoid some issues while using `math` package.

### Basic commands in Jupyter

* Note that in `Jupyter` you add new lines by typing "b" from your keyboard whilst the notebook is opened.
* Avoid runing the entire code in a single cell in  order to understand the steps.
* Use "ctrl + enter" to execute each line if you want to get the output.
* Use "dd" outside a cell to delete it.
* Use "a" outside a cell to add a new cell above it.
* Use "b" outside as cell to add a new cell below it.
* Running the last cell should execute the permutations as program output.

## Running the tests

* I used Ubuntu (18.04 bionic) to launch Jupyter Notebook on localhost.
* Localhost instantiates while using <b>$ jupyter notebook</b> in the terminal.
* Check if Jupyter is correctly installed: <b>$ jupyter --version</b>

## Built With

* [Jupyter](http://jupyter.org/) - An open source software for creating notebooks
* [Numpy](http://jupyter.org/) - The fundamental package for scientific computing with Python
* [Math](https://docs.python.org/3/library/itertools.html) - Mathematical functions defined by the C standar
* [PIL](https://pillow.readthedocs.io/en/3.0.x/reference/ImageDraw.html) - Create images, annotate, retouch existing ones
* [Requests](https://pypi.org/project/requests/) - A non-GMO HTTP library for Python, safe for human consumption

## Versioning

I used no vesioning system for this gist, which <b>repos status<b> is flagged as <b>concept<b> because it is intended to be a demo or POC (proof-of-concept).

## Author

* **Isaac Arnault** - Suggesting a way to render edges for specific images such as: coins, architecture images.

## Practicum

Store the below image remotely (on your IDE / PC) and try to detect edges using `Python`.<br><br>
[parking.png](https://postimg.cc/hXszXTfr)
