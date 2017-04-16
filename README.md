# pip-save
bringing npm like behavior to pip including init & save.

[![asciicast](https://asciinema.org/a/6glxw1um5qrp52zzn2hyi5d5s.png)](https://asciinema.org/a/6glxw1um5qrp52zzn2hyi5d5s)

Installation
------------

	source <(curl -sSLk https://raw.githubusercontent.com/abhiomkar/pip-save/master/install)

Usage
-----

Create virtual environment & install packages

	$ mkdir my-new-project && cd my-new-project
	$ pip init
	$ pip --save install request numpy scipy
	$ cat requirements.txt
	numpy==1.10.1
	request==0.0.2
	scipy==0.16.1
	wheel==0.24.0

Install dependencies

	$ pip install

Blog
----

Read my blog post here:

http://blog.abhiomkar.in/2015/11/12/pip-save-npm-like-behaviour-to-pip

TODO
----

* Generate `setup.py` on `pip init` just like [pip-init](https://github.com/juanpabloaj/pip-init)

Author
------

Abhinay Omkar [@abhiomkar](http://twitter.com/abhiomkar)
