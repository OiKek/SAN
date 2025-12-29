# Instalation and execution

### 1. Clone the repository

For cloning the repository into your local device, run the command
```sh
git clone git@github.com:OiKek/SAN.git
```
or
```sh
git clone https://github.com/OiKek/SAN
```
After cloning, move into the project directory:
```sh
cd SAN
```

### 2. Local settings

In the git folder SAN, create a virtual environment.

```sh
python3 -m venv venv
```
Activate the local environment.
```sh
source venv/bin/activate
```

### 3. Install requirements

It is important to activate the virtual environment before installing all packages.
Then run the following command to install all libraries needed to run the project.

```sh
pip install -r requirements.txt
```

Notes:

- The virtual environment folder (venv) is not included in the repository (condition already included in the .gitignore)
- The requirements.txt file is used to reproduce the project environment
- Make sure you are using a compatible Python version (e.g. Python 3.11+)

To deactivate the virtual environment when finished, run:
```sh
deactivate
```
