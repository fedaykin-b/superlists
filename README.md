# Superlists Project

This project is suggested by the book [Test-Driven Development with Python: Obey the Testing Goat: Using Django, Selenium, and JavaScript](https://www.amazon.com.br/Test-Driven-Development-Python-Selenium-JavaScript-ebook/dp/B074HXXXLS/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=&sr=).

It shall be built as I progress on the lectures.

# instructions

It's good to have a virtualenv configured on your PC. The book recommends a helper module called *virtualenvwrapper*. If you use Windows as I do, you could use [this port of the module to windows batch](https://pypi.org/project/virtualenvwrapper-win/).

1. Start a virtualenv:
```
# on macOS/Linux:
mkvirtualenv --python=python3.6 your_virtualenv_name

# on Windows
mkvirtualenv --python=python your_virtualenv_name

```
If you already have a virtualenv, you can activate it with
```
workon your_virtualenv_name
```
Use the ```deactivate``` command to exit it.

2. Install packages on your env:
```
pip install -r requirements.txt
```
3. Download the [ChromeDriver](http://chromedriver.chromium.org/downloads).
Unzip it and make sure its path is included on the PATH system variable. If you don't do this, make sure the webdriver in selenium module can find the driver by passing its path on calling:
```python3
browser = webdriver.Chrome('/path/to/chromedriver')

```



