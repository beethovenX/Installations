# Installations

## How to Intsall Python on Mac OS -- Self Notes

### Step 1: Install Python Using Homebrew

#### Install Homebrew
1. Open Terminal.
2. Run the following command to install Homebrew:
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

3.	Follow the on-screen instructions to complete the installation.

#### Install Python

1.	Use Homebrew to install Python:
    ```bash
    brew install python

2. Follow the on-screen instructions to complete the installation.

#### Verify Installation

1. Confirm that Python is installed by checking its version:
    ```bash
    python3 --version

#### Upgrade pip

1. Upgrade the pip package manager:
    ```bash
    python3 -m pip install --upgrade pip

### Step 2: Install Python Using Pyenv

#### Install Pyenv via Homebrew

1. Run the following command in Terminal to install pyenv:
    ```bash
    brew install pyenv

2. Follow the on-screen instructions to complete the installation.

#### Configure Pyenv

1. Add the following lines to your shell configuration file:
   •	For Zsh (~/.zshrc):
   ```bash
   export PYENV_ROOT="$HOME/.pyenv"
   export PATH="$PYENV_ROOT/bin:$PATH"
   eval "$(pyenv init --path)" 

2. Reload your shell configuration:
    ```bash
    source ~/.zshrc

#### Install a Python Version

1. Use pyenv to install a specific version of Python:
   ```bash 
    pyenv install 3.x.x  # Replace "3.x.x" with the desired version

2.	Follow the on-screen instructions to complete the installation.

#### Verify Installation

1.	Confirm that Python is installed by checking its version:
    ```bash
    python3 --version