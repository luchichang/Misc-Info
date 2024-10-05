# Creating the virtual Environment for Python

## description,


## pre-requisite

* install python and pip, by following the instructions in the given link
``` bash
  https://www.python.org/downloads/
```
* ensure the packages are running as needed,

``` bash
  python --version
  pip --version
```
(if the console output displayed the software current version then we are good to go)


## steps

* install the ___virtualenv___ python module which is responsible for creating python virtual environment

``` bash
 python -m venv <environment name>
```

* activate the virtual environment

``` bash
./<venv name>/Scripts/activate
```

* now you can install the necessary packages and its dependencies for project specific without changing/affecting the global packages

* once project is completed if you want to document the packages type 
``` bash
pip freeze > requirements.txt
```

* for exiting the virtual environment
``` bash
deactivate
```




