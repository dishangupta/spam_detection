# Setup
Clone repository
```
   git clone https://github.com/dishangupta/spam_detection.git
   cd spam_detection
```

Install virtualenvwrapper for Python environment
```
   pip install virtualenvwrapper
   export WORKON_HOME=$HOME/.virtualenvs
   export PROJECT_HOME=$HOME/Devel
   source /usr/local/bin/virtualenvwrapper.sh
```   

Setup Python environment
```
   mkvirtualenv venv
   pip install --upgrade --requirement requirements.txt
```

# Run spam detection algorithm
Launch IPython notebook,
```
ipython notebook
```

Open `spam_classifiers.ipynb`, and step through the code for training and testing
