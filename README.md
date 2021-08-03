# NozamatoN
just another website

## Installation 

## Linux
### Python Installation
<code>sudo apt update</code>
<code>sudo apt upgrade -y</code>
<code>sudo apt install python</code>\
<code>python3 --version</code> To verify the installation

### Pipenv Install 
<code>python3 -m pip install pipenv</code>
<code>pip freeze</code> To verify the installation

### Create a new folder
<code>cd ~</code>
<code>mkdir _filename_</code>
<code>cd _filename_</code>

### Virtual Environment
<code>pipenv install --python 3.9</code>
#### Initialise Virtual Environment
<code>pipenv shell</code>

## Windows
### Python Download 
Download the latest version of python [here](https://www.python.org/download/)

### Python Install
While installing tick the following
- Add python 3.9 to PATH
- pip
- Install for all users - add pytho to environment variables - Create shortcuts for installed applications - Precomplie standard library
- Customize install location C:\Python39
- Hit <code>Install</code>

### Install Verification
Search for windows powershell and click 'run as administrator'
<code>python -V</code>
If there is an error try to restart your device. Uninstall python and repeat the Installation process.
<code>pip freeze</code>

### Pipenv Install
Use powershell
<code>python -m pip install pipenv</code>

### Verify 
<code>pipenv</code>

### Create a folder
<code>cd ~</code>
<code>mkdir _filename_</code>
<code>cd _filename_</code>

### Virtual Environment
<code>cd _filename_</code>
<code>pipenv install</code>
#### Initialise Virtual Environment
<code>pipenv shell</code>

<code>pip freeze</code>
You will find that there are no packages installed
This is because you are in a virtual environment 

To exit the virtual environment
<code>deactivate</code>
<code>exit</code>

## Django Installation 
Once you have completed the installation of pipenv and verified it
You need to start the virtual environment
<code>pipenv shell</code>
<code>pipenv install Django==3.2.6</code>
Change the 3.2.6 with the latest or the version you want to install.

