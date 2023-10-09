# catboost_1

# Setup
If a version of Python `3.10` already present, skip to Step 5.


Step 1:
```shell
brew install pyenv
```
Step 2
```shell
pyenv install 3.10.10
```
Add this to your `~/.profile` and restart your terminal
```shell
#### Python ####
export PYENV_ROOT="$HOME/.pyenv"
command -v pyenv >/dev/null || export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init -)"
```

Step 3
```shell
pyenv shell 3.10.10
```

Step 4
```shell
pip install --upgrade pip
```

Step 5
```shell
pip install jupyterlab keyring ipywidgets
```

Finally, launch JupyterLab and open `california.ipynb` notebook 
```shell
jupyter-lab california.ipynb
```