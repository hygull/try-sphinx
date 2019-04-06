### pip install sphinx

> pip install history for sphinx on MAC OS X


```bash
Collecting sphinx
  Using cached https://files.pythonhosted.org/packages/17/a4/338f9cbc334dd27c972ea9aae3e054068c9b3a642c8abb1f67f93a59a85e/Sphinx-2.0.0-py2.py3-none-any.whl
Collecting sphinxcontrib-qthelp (from sphinx)
  Using cached https://files.pythonhosted.org/packages/ce/5b/4747c3ba98b3a3e21a66faa183d8f79b9ded70e74212a7988d236a6eb78a/sphinxcontrib_qthelp-1.0.2-py2.py3-none-any.whl
Collecting snowballstemmer>=1.1 (from sphinx)
  Using cached https://files.pythonhosted.org/packages/d4/6c/8a935e2c7b54a37714656d753e4187ee0631988184ed50c0cf6476858566/snowballstemmer-1.2.1-py2.py3-none-any.whl
Requirement already satisfied: setuptools in ./venv3.6.7/lib/python3.6/site-packages (from sphinx) (41.0.0)
Collecting docutils>=0.12 (from sphinx)
  Using cached https://files.pythonhosted.org/packages/36/fa/08e9e6e0e3cbd1d362c3bbee8d01d0aedb2155c4ac112b19ef3cae8eed8d/docutils-0.14-py3-none-any.whl
Collecting Jinja2>=2.3 (from sphinx)
  Using cached https://files.pythonhosted.org/packages/1d/e7/fd8b501e7a6dfe492a433deb7b9d833d39ca74916fa8bc63dd1a4947a671/Jinja2-2.10.1-py2.py3-none-any.whl
Collecting sphinxcontrib-serializinghtml (from sphinx)
  Using cached https://files.pythonhosted.org/packages/57/b3/3648e48fa5682e61e9839d62de4e23af1795ceb738d68d73bd974257a95c/sphinxcontrib_serializinghtml-1.1.3-py2.py3-none-any.whl
Collecting sphinxcontrib-jsmath (from sphinx)
  Using cached https://files.pythonhosted.org/packages/c2/42/4c8646762ee83602e3fb3fbe774c2fac12f317deb0b5dbeeedd2d3ba4b77/sphinxcontrib_jsmath-1.0.1-py2.py3-none-any.whl
Collecting Pygments>=2.0 (from sphinx)
  Using cached https://files.pythonhosted.org/packages/13/e5/6d710c9cf96c31ac82657bcfb441df328b22df8564d58d0c4cd62612674c/Pygments-2.3.1-py2.py3-none-any.whl
Collecting sphinxcontrib-htmlhelp (from sphinx)
  Using cached https://files.pythonhosted.org/packages/8c/55/e3d2302b033b25b4a67abe436cabb19e3bfa17fbc7b9ec44b1bfd9a41dbb/sphinxcontrib_htmlhelp-1.0.1-py2.py3-none-any.whl
Collecting requests>=2.5.0 (from sphinx)
  Using cached https://files.pythonhosted.org/packages/7d/e3/20f3d364d6c8e5d2353c72a67778eb189176f08e873c9900e10c0287b84b/requests-2.21.0-py2.py3-none-any.whl
Collecting packaging (from sphinx)
  Using cached https://files.pythonhosted.org/packages/91/32/58bc30e646e55eab8b21abf89e353f59c0cc02c417e42929f4a9546e1b1d/packaging-19.0-py2.py3-none-any.whl
Collecting sphinxcontrib-applehelp (from sphinx)
  Using cached https://files.pythonhosted.org/packages/13/9a/4428b3114d654cb1cd34d90d5e6fab938d5436f94a571155187ea1dd78b4/sphinxcontrib_applehelp-1.0.1-py2.py3-none-any.whl
Collecting babel!=2.0,>=1.3 (from sphinx)
  Using cached https://files.pythonhosted.org/packages/b8/ad/c6f60602d3ee3d92fbed87675b6fb6a6f9a38c223343ababdb44ba201f10/Babel-2.6.0-py2.py3-none-any.whl
Collecting imagesize (from sphinx)
  Using cached https://files.pythonhosted.org/packages/fc/b6/aef66b4c52a6ad6ac18cf6ebc5731ed06d8c9ae4d3b2d9951f261150be67/imagesize-1.1.0-py2.py3-none-any.whl
Collecting alabaster<0.8,>=0.7 (from sphinx)
  Using cached https://files.pythonhosted.org/packages/10/ad/00b090d23a222943eb0eda509720a404f531a439e803f6538f35136cae9e/alabaster-0.7.12-py2.py3-none-any.whl
Collecting sphinxcontrib-devhelp (from sphinx)
  Using cached https://files.pythonhosted.org/packages/b0/a3/fea98741f0b2f2902fbf6c35c8e91b22cd0dd13387291e81d457f9a93066/sphinxcontrib_devhelp-1.0.1-py2.py3-none-any.whl
Collecting MarkupSafe>=0.23 (from Jinja2>=2.3->sphinx)
  Using cached https://files.pythonhosted.org/packages/f0/00/a6aea33f5598b080b86d6b6d1214b51afe3ffa6100b902d5aa465080083f/MarkupSafe-1.1.1-cp36-cp36m-macosx_10_6_intel.whl
Collecting chardet<3.1.0,>=3.0.2 (from requests>=2.5.0->sphinx)
  Using cached https://files.pythonhosted.org/packages/bc/a9/01ffebfb562e4274b6487b4bb1ddec7ca55ec7510b22e4c51f14098443b8/chardet-3.0.4-py2.py3-none-any.whl
Collecting idna<2.9,>=2.5 (from requests>=2.5.0->sphinx)
  Using cached https://files.pythonhosted.org/packages/14/2c/cd551d81dbe15200be1cf41cd03869a46fe7226e7450af7a6545bfc474c9/idna-2.8-py2.py3-none-any.whl
Collecting certifi>=2017.4.17 (from requests>=2.5.0->sphinx)
  Using cached https://files.pythonhosted.org/packages/60/75/f692a584e85b7eaba0e03827b3d51f45f571c2e793dd731e598828d380aa/certifi-2019.3.9-py2.py3-none-any.whl
Collecting urllib3<1.25,>=1.21.1 (from requests>=2.5.0->sphinx)
  Using cached https://files.pythonhosted.org/packages/62/00/ee1d7de624db8ba7090d1226aebefab96a2c71cd5cfa7629d6ad3f61b79e/urllib3-1.24.1-py2.py3-none-any.whl
Collecting six (from packaging->sphinx)
  Using cached https://files.pythonhosted.org/packages/73/fb/00a976f728d0d1fecfe898238ce23f502a721c0ac0ecfedb80e0d88c64e9/six-1.12.0-py2.py3-none-any.whl
Collecting pyparsing>=2.0.2 (from packaging->sphinx)
  Using cached https://files.pythonhosted.org/packages/de/0a/001be530836743d8be6c2d85069f46fecf84ac6c18c7f5fb8125ee11d854/pyparsing-2.3.1-py2.py3-none-any.whl
Collecting pytz>=0a (from babel!=2.0,>=1.3->sphinx)
  Using cached https://files.pythonhosted.org/packages/61/28/1d3920e4d1d50b19bc5d24398a7cd85cc7b9a75a490570d5a30c57622d34/pytz-2018.9-py2.py3-none-any.whl
Installing collected packages: sphinxcontrib-qthelp, snowballstemmer, docutils, MarkupSafe, Jinja2, sphinxcontrib-serializinghtml, sphinxcontrib-jsmath, Pygments, sphinxcontrib-htmlhelp, chardet, idna, certifi, urllib3, requests, six, pyparsing, packaging, sphinxcontrib-applehelp, pytz, babel, imagesize, alabaster, sphinxcontrib-devhelp, sphinx
Successfully installed Jinja2-2.10.1 MarkupSafe-1.1.1 Pygments-2.3.1 alabaster-0.7.12 babel-2.6.0 certifi-2019.3.9 chardet-3.0.4 docutils-0.14 idna-2.8 imagesize-1.1.0 packaging-19.0 pyparsing-2.3.1 pytz-2018.9 requests-2.21.0 six-1.12.0 snowballstemmer-1.2.1 sphinx-2.0.0 sphinxcontrib-applehelp-1.0.1 sphinxcontrib-devhelp-1.0.1 sphinxcontrib-htmlhelp-1.0.1 sphinxcontrib-jsmath-1.0.1 sphinxcontrib-qthelp-1.0.2 sphinxcontrib-serializinghtml-1.1.3 urllib3-1.24.1

```