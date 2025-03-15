# deploy-python-applications-on-google-cloud-platform
From Training to the Cloud: Deploy Machine Learning Models on GCP with Python

### Install pyenv
`pyenv` is a Python version management tool. To install it, follow the instructions below:

1. **Update the system:** Open the terminal and run:
```
sudo apt update
sudo apt upgrade
```
2. **Install dependencies:** Make sure you have the necessary dependencies to compile `pyenv`:
```
sudo apt install -y build-essential libssl-dev zlib1g-dev libbz2-dev \
libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev \
xz-utils tk-dev liblzma-dev libyaml-dev libgdbm-dev libffi-dev libgmp-dev \
libncurses-dev libbz2-dev libreadline-dev libssl-dev libsqlite3-dev
```
3. **Install pyenv manually:** You can install pyenv with the following command:
```
curl https://pyenv.run | bash
```

4. **Add `pyenv` to your shell:** Add the lines below to your `~/.bashrc`, `~/.zshrc`, or the configuration file for the shell you use:
```
export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv init -)"
```
5. **Reload the shell configuration:** After editing the shell configuration file, reload the shell:
```
source ~/.bashrc
```

6. **Verify the installation:** Now, you can verify that pyenv was installed correctly with:
```
pyenv --version
```

### Install poetry
`Poetry` is a tool for managing dependencies and creating virtual environments. To install it, use the following command:
```
curl -sSL https://install.python-poetry.org | python3 -
```
After installation, add Poetry to your PATH if necessary:
```
export PATH="$HOME/.local/bin:$PATH"
```
Check if poetry was installed correctly:
```
poetry --version
```

### Virtual Environment
1. With `pyenv`, you can install the version of Python you want to use in the virtual environment.

```
pyenv install 3.10.4
```
2. Set the global or local Python version
To set the Python version globally (for all projects), use:
```
pyenv global 3.10.4
# or
pyenv local 3.10.4 # to set local version
```

3. Start poetry in existing project
In your project directory, run the command:
```
poetry init
```

4. Create virtual environment
```
poetry env use $(which python)
```

5. Check the virtual environment
```
poetry env info
```

6. Activate the virtual environment
```
poetry env activate
source .venv/bin/activate
```

7. Install dependencies
```
poetry install --no-root
```