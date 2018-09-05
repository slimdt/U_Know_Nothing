## install virtualenv on mac
[official doc](https://virtualenv.pypa.io/en/stable/) <br/>
[another link](https://anil.io/blog/python/pyenv/using-pyenv-to-install-multiple-python-versions-tox/)
## create a virtualenv
virtualenv -p python folder_name <br />
(here I use pyenv to do the management of python versions, so python version is just pyenv global, you can change to the specific version of python you need by pyenv global 3.5.6 for example or replace python with its absolute path)

## activate the virtualenv
cd folder_name <br />
source bin/activate

## deactivate the virtualenv

deactivate 

