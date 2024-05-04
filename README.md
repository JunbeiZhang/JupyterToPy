# JupyterToPy
When we get some code from github, it may be notebook(jupyter). At the same time, we want to use the code as python code, then we can use this method.

If you don't have nbconvert installed yet, you can install it via pip:
```
pip install nbconvert
```
Open your command line tool (such as Terminal on macOS/Linux, CMD or PowerShell on Windows) and use the following command:
```
jupyter nbconvert --to script [YOUR_NOTEBOOK].ipynb
```
For example:
```
jupyter nbconvert --to script C:\python_code\hello_world.ipynb
```
