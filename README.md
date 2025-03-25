```bash
# Install pip if not already installed
pacman -S --overwrite="*" mingw-w64-x86_64-python-pip

# add this to ~/.bashrc
export PATH="$PATH:/c/Users/user/.local/bin/"
# in some environments the .local folder is stored somewhere else
#export PATH=$PATH:/home/user/.local/bin'

python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip

# Setup tools are optional
#pip install --upgrade setuptools wheel 
pip install bython
```

Run your example

```bash
bython example.by
```

