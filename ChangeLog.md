# ChangeLog #

## 0.4.0 ##
**pypreprocessor.py**
  * cleaned and refactored core code
  * fixed [Bug #1](https://code.google.com/p/pypreprocessor/issues/detail?id=1)


---


## 0.3.0 ##
**pypreprocessor.py**
  * cleaned and refactored the core codebase
  * added version and author metadata

**setup.py**
  * updated to fetch metadata directly from the appropriate modules

**README.txt**
  * updated so it no longer sucks
  * moved install info into INSTALL.txt

**CHANGELOG.txt**
  * added with a link to the online changelog for completeness

**TODO.txt**
  * added with a link to the online TODO for completeness

**INSTALL.txt**
  * added


---


## 0.2.0 ##
**pypreprocessor.py**
  * cleaned the code
  * can strip meta-tags on the fly
  * added #exclude directive
  * added #endexclude directive
  * added error handling to all the directives
  * modified error tracebacks to be more concise when tracking code executed on-the-fly

**test.py**
  * improved the tests to provide better coverage

**py2and3.py**
  * cleaned code and added docblock

**debug2production.py**
  * added
  * shows a working example of the different processing modes

**LICENSE.txt**
  * added

**README.txt**
  * added

**setup.py**
  * added
  * to give users an option to easily install the library on their systems
  * to integrate pypreprocessor directly with the PYPI (PYthon Package Index)


---


## 0.1.0 ##
**Initial Release**

**pypreprocessor.py**
  * added
  * added #define directive
  * added #undef directive
  * added #ifdef directive
  * added #else directive
  * added #endif directive
  * can output post-processed source to a file
  * can execute post-processed source on-the-fly
  * can process an external source file
  * can self-consume a source file

**test.py**
  * added
  * provides unit tests for all of the directives

**.hgignore**
  * added
  * ignores .pyc (compiled bytecode) files
  * ignores files not under source control