# Mentoring resources

## Data scraping example

A Python web scraping 101 tutorial! What you'll do:

- Retrieve the HTML of a provided website via the `requests` package
- Parse HTML with the `bs4` (BeautifulSoup) package
- Use BeautifulSoup `find_all` to find content and links of anchor tags on the page requested

### Setup

1. Install dependencies

*Note: I like to use virtual environments for my dependencies; it makes things cleaner if you have multiple Python projects running.* 
*Check out https://github.com/pyenv/pyenv#installation to manage your python versions with `pyenv`, and*
*https://github.com/pyenv/pyenv#installation to install the `virtualenv` plugin for `pyenv`.*
*Be sure to create + activate the environment before installing the dependencies!*

Install all the dependencies with: `pip install -r requirements.txt`

2. Run the notebook

`jupter notebook` will bring you to the notebook tree in the browser. Click on `Python scraping example.ipynb` to open the notebook. 

Each invidiual cell contains Python code that will be executed in the browser and displayed to you. 
Click into a cell and press "enter" to run the code.
