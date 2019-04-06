# try-sphinx

A project to create a beautiful documentation using Sphinx.

### Quick start

1. Create any directory & navigate inside that.
	
	+ `cd ~/Projects/Python3/Sphinx/`

	+ `mkdir try_sphinx`

	+ `cd try_sphinx/`


2. Create virtual environment & activate it.

	> **Note:** In windows, you can try `.\venv\Scripts\activate`.

	+ `python3 -m virtaulenv venv`
	
	+ `source venv/bin/activate`

3. Install **sphinx**.

	+ `pip install sphinx`


> You can have a look at [pip install history for sphinx on MAC OS X](./files/sphinx-install-history.md) for full install history of **sphinx**.

```bash
(venv3.6.7)Rishikeshs-Air:try_sphinx hygull$ pip install sphinx
You are using pip version 6.0.8, however version 19.0.3 is available.
You should consider upgrading via the 'pip install --upgrade pip' command.
Collecting sphinx
  Downloading https://files.pythonhosted.org/packages/17/a4/338f9cbc334dd27c972ea9aae3e054068c9b3a642c8abb1f67f93a59a85e/Sphinx-2.0.0-py2.py3-none-any.whl (3.2MB)
    100% |################################| 3.2MB 111kB/s 
Collecting docutils>=0.12 (from sphinx)
...

```

4. Create a directory named **docs** and navigate inside that.

	+ `mkdir docs`

	+ `cd docs`

5. In here, run the below command. You can see output [here](./files/sphinx-quickstart-output.md) if you wish to see how it appeared in my case.

	+ `sphinx-quickstart`


6. Finally, run the below 2 commands one after one

	> **Note:** In Windows, you can try **start source\html\index.html** to open the index.html file in your browser. 
	>
	>Anyways, you can open the directory using Explorer/Finder etc. 	and click/dbclick (based on settings) to open it and see the page in your browser.
	> 
	>In my case, I am on MAC OS X. 

	+ `make html`

	+ `open source/html/index.html`

Now, you can see a beauiful HTML page generated for you.



### Quick overview of my terminal

```bash
Rishikeshs-Air:~ hygull$ cd ~/Projects/Python3/Sphinx/
Rishikeshs-Air:Sphinx hygull$ 
Rishikeshs-Air:Sphinx hygull$ mv try_sphinx/ try_sphinx2
Rishikeshs-Air:Sphinx hygull$ 
Rishikeshs-Air:Sphinx hygull$ mkdir try_sphinx
Rishikeshs-Air:Sphinx hygull$ 
Rishikeshs-Air:Sphinx hygull$ cd try_sphinx
Rishikeshs-Air:try_sphinx hygull$ 
```

```bash
Rishikeshs-Air:try_sphinx hygull$ python3 -m virtualenv venv3.6.7
Using base prefix '/Library/Frameworks/Python.framework/Versions/3.6'
New python executable in /Users/hygull/Projects/Python3/Sphinx/try_sphinx/venv3.6.7/bin/python3
Also creating executable in /Users/hygull/Projects/Python3/Sphinx/try_sphinx/venv3.6.7/bin/python
Installing setuptools, pip, wheel...
done.
Rishikeshs-Air:try_sphinx hygull$
```

```bash
Rishikeshs-Air:try_sphinx hygull$ source ./venv3.6.7/bin/activate
(venv3.6.7) Rishikeshs-Air:try_sphinx hygull$ 
```

```bash
(venv3.6.7)Rishikeshs-Air:try_sphinx hygull$ pip install sphinx
Collecting sphinx
  Using cached https://files.pythonhosted.org/packages/17/a4/338f9cbc334dd27c972ea9aae3e054068c9b3a642c8abb1f67f93a59a85e/Sphinx-2.0.0-py2.py3-none-any.whl
...
```


```bash
(venv3.6.7) Rishikeshs-Air:try_sphinx hygull$ mkdir docs
```

```bash
(venv3.6.7) Rishikeshs-Air:try_sphinx hygull$ cd docs/
```

```bash
(venv3.6.7) Rishikeshs-Air:docs hygull$ make html
Running Sphinx v2.0.0
making output directory... done
building [mo]: targets for 0 po files that are out of date
building [html]: targets for 1 source files that are out of date
updating environment: 1 added, 0 changed, 0 removed
reading sources... [100%] index                                                          
looking for now-outdated files... none found
pickling environment... done
checking consistency... done
preparing documents... done
writing output... [100%] index                                                           
generating indices... genindex
writing additional pages... search
copying static files... done
copying extra files... done
dumping search index in English (code: en) ... done
dumping object inventory... done
build succeeded.

The HTML pages are in build/html.
```


```bash
(venv3.6.7) Rishikeshs-Air:docs hygull$ open build/html/index.html 
(venv3.6.7) Rishikeshs-Air:docs hygull$ 
```

### References

- [x] [Getting Started with Sphinx](https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html)

- [x] [Video guide](https://youtu.be/oJsUvBQyHBs)
