### pip install recommonmark

> pip install history for sphinx on MAC OS X

[Click here](https://hygull.github.io/try-sphinx/) to return to the previous page.


```bash
Rishikeshs-MacBook-Air:try_sphinx hygull$ source ./venv3.6.7/bin/activate
(venv3.6.7) Rishikeshs-MacBook-Air:try_sphinx hygull$ pip install recommonmark
Collecting recommonmark
  Downloading https://files.pythonhosted.org/packages/9b/3d/92ea48401622510e57b4bdaa74dc9db2fb9e9e892324b48f9c02d716a93a/recommonmark-0.5.0-py2.py3-none-any.whl
Requirement already satisfied: docutils>=0.11 in ./venv3.6.7/lib/python3.6/site-packages (from recommonmark) (0.14)
Requirement already satisfied: sphinx>=1.3.1 in ./venv3.6.7/lib/python3.6/site-packages (from recommonmark) (2.0.0)
Collecting commonmark>=0.7.3 (from recommonmark)
  Downloading https://files.pythonhosted.org/packages/ab/ca/439c88039583a29564a0043186875258e9a4f041fb5c422cd387b8e10175/commonmark-0.8.1-py2.py3-none-any.whl (47kB)
    100% |████████████████████████████████| 51kB 556kB/s 
Requirement already satisfied: Pygments>=2.0 in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (2.3.1)
Requirement already satisfied: sphinxcontrib-jsmath in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (1.0.1)
Requirement already satisfied: sphinxcontrib-qthelp in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (1.0.2)
Requirement already satisfied: alabaster<0.8,>=0.7 in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (0.7.12)
Requirement already satisfied: setuptools in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (41.0.0)
Requirement already satisfied: sphinxcontrib-serializinghtml in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (1.1.3)
Requirement already satisfied: Jinja2>=2.3 in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (2.10.1)
Requirement already satisfied: sphinxcontrib-htmlhelp in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (1.0.1)
Requirement already satisfied: requests>=2.5.0 in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (2.21.0)
Requirement already satisfied: snowballstemmer>=1.1 in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (1.2.1)
Requirement already satisfied: packaging in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (19.0)
Requirement already satisfied: imagesize in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (1.1.0)
Requirement already satisfied: sphinxcontrib-devhelp in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (1.0.1)
Requirement already satisfied: babel!=2.0,>=1.3 in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (2.6.0)
Requirement already satisfied: sphinxcontrib-applehelp in ./venv3.6.7/lib/python3.6/site-packages (from sphinx>=1.3.1->recommonmark) (1.0.1)
Collecting future (from commonmark>=0.7.3->recommonmark)
  Using cached https://files.pythonhosted.org/packages/90/52/e20466b85000a181e1e144fd8305caf2cf475e2f9674e797b222f8105f5f/future-0.17.1.tar.gz
Requirement already satisfied: MarkupSafe>=0.23 in ./venv3.6.7/lib/python3.6/site-packages (from Jinja2>=2.3->sphinx>=1.3.1->recommonmark) (1.1.1)
Requirement already satisfied: idna<2.9,>=2.5 in ./venv3.6.7/lib/python3.6/site-packages (from requests>=2.5.0->sphinx>=1.3.1->recommonmark) (2.8)
Requirement already satisfied: urllib3<1.25,>=1.21.1 in ./venv3.6.7/lib/python3.6/site-packages (from requests>=2.5.0->sphinx>=1.3.1->recommonmark) (1.24.1)
Requirement already satisfied: chardet<3.1.0,>=3.0.2 in ./venv3.6.7/lib/python3.6/site-packages (from requests>=2.5.0->sphinx>=1.3.1->recommonmark) (3.0.4)
Requirement already satisfied: certifi>=2017.4.17 in ./venv3.6.7/lib/python3.6/site-packages (from requests>=2.5.0->sphinx>=1.3.1->recommonmark) (2019.3.9)
Requirement already satisfied: six in ./venv3.6.7/lib/python3.6/site-packages (from packaging->sphinx>=1.3.1->recommonmark) (1.12.0)
Requirement already satisfied: pyparsing>=2.0.2 in ./venv3.6.7/lib/python3.6/site-packages (from packaging->sphinx>=1.3.1->recommonmark) (2.3.1)
Requirement already satisfied: pytz>=0a in ./venv3.6.7/lib/python3.6/site-packages (from babel!=2.0,>=1.3->sphinx>=1.3.1->recommonmark) (2018.9)
Building wheels for collected packages: future
  Building wheel for future (setup.py) ... done
  Stored in directory: /Users/hygull/Library/Caches/pip/wheels/0c/61/d2/d6b7317325828fbb39ee6ad559dbe4664d0896da4721bf379e
Successfully built future
Installing collected packages: future, commonmark, recommonmark
Successfully installed commonmark-0.8.1 future-0.17.1 recommonmark-0.5.0
(venv3.6.7) Rishikeshs-MacBook-Air:try_sphinx hygull$ 
```