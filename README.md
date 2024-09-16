# cv
These are the practical sessions and homeworks for the UCU computer vision class. 

J. Matias Di Martino
matias.di.martino.uy@gmail.com
---------
## Versions and releases:
- 0.1.0: First release.

## Installation 
### Locally
1. Clone the repo
2. Set pyenv (check https://github.com/pyenv/pyenv#installation)
3. Use pyenv to install the python of version you want to use (in this case 3.10.x)
```
$ pyenv install 3.10 
```
4. Set your current project to use the version of python just intalled. 
```
$ pyenv local 3.10
```
This will create a .python-version file that pyenv uses to set the python version for the current project.
5. Now we will create a virtual environment and install the dependencies. 
```
$ python -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```
### Other useful commands
To leave an environment just type 
```
$deactivate
```
or 
```
$source deactivate
```

To check the python version you are using type and where is set by pyenv type
```
$pyenv version 
```

To check if you are using the right environment type
```
$which python
```
and check it points to the right folder. 

## Resources 
- https://www.numerical-tours.com/
- https://www.pyimagesearch.com/

