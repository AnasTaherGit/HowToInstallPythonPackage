# HowToInstallPythonPackage

a Hello World package for testing python packages installation

## Installation procedure for Windows

To install a package in your default python installation you need to run the command :

```batch
python setup.py install
```

if you want instead to install it in a virtual environment for the project you simply have to activate the python virtual environment before the install command

```batch
python -m venv .venv
.\.venv\Scripts\activate
python setup.py install
```

Or you can instead run the batch file 'Setup.bat'

```batch
setup.bat
```
