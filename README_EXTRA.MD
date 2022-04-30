If you have a fresh computer environment:

# install pip
```
curl https://bootstrap.pypa.io/get-pip.py > get-pip.py

python3 get-pip.py
```

## set `PATH` forn pip binary
export PATH=$PATH:~/.local/bin

# install virtualenvwrapper
```
pip install virtualenvwrapper
pip3 install virtualenvwrapper
source ~/.local/bin/virtualenvwrapper.sh
```

## make virtual environment for pytorch
```
mkvirtualenv pytorch
workon pytorch 
```

# install pytorch
## if you use a linux machine
```
pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cpu # linux
```
## if you use a mac machine
```
pip install torch torchvision torchaudio # mac without CUDA GPU
```

# install wget if you don't have in your system
```
brew install wget
```

