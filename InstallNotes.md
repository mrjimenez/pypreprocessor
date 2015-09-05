## Install ##

### Simple ###

  1. download and unpack the contents.
  1. copy pypreprocessor.py to the directory where it will be used
_Note: pypreprocessor is intentionally kept small and self-contained in a single source file to make it easy to use and/or package with other libraries/applications. As long as pypreprocessor exists this will remain true._

### Using pip ###

  1. in a terminal enter:

```
sudo pip install pypreprocessor
```
_Note: sudo is only necessary if the location of the python libraries requires root priveledges to access._

This is the easiest method to install pypreprocessor for system-wide use. The only downside is, pip currently only supports installing to python 2x.

### Using setup.py ###

  1. download and unpack the contents
  1. open a terminal in the directory containing the contents
  1. in the terminal enter:

```
sudo python setup.py install
```
_Note: sudo is only necessary if the location of the python libraries requires root priveledges to access._

To install for python 3x repeat steps 1 & 2 and for step 3 enter:
```
sudo python3 setup.py install
```