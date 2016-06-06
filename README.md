#cdnjs library importer using python

Now only support NPM package

usage:

importer.py [-h] --lib-name LIB_NAME --git-url GIT_URL [--npm-pkg NPM_PKG] --lib-author LIB_AUTHOR --issue-num ISSUE_NUM

cdnjs importer

optional arguments:

-h, --help                              show this help message and exit

--lib-name LIB_NAME, -l LIB_NAME        The library name wanted to import to cdnjs

--git-url GIT_URL, -g GIT_URL           The git repository url of the library

--npm-pkg NPM_PKG, -n NPM_PKG           The npm package name of the library

--lib-author LIB_AUTHOR, -a LIB_AUTHOR  The author's github account of the library

--issue-num ISSUE_NUM, -i ISSUE_NUM     The issue number of cdnjs

dependencies:

pip install gitpython

reference:

http://gitpython.readthedocs.io/en/stable/intro.html
