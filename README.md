Classifying tweets to based on whether they refer to real disasters.

# Getting started
- From the project root directory, create a virtual environment

        python -m virtualenv venv

- Activate environment

        source venv/bin/activate

- Install packages

        python -m pip install -r requirements.txt


- Follow the instructions [here](https://github.com/Kaggle/kaggle-api) to setup the kaggle API (needed for downloading data and pulling/pushing kernels)

- Download files associated with the competition

        kaggle competitions download -c [COMPETITION]


#  Kaggle API
- Create a kernel

        kaggle kernels init -p /path/to/kernel


- Push a kernel and run on Kaggle
        
        kaggle kernels push -p /path/to/kernel

- Pull kernel 
        
        kaggle kernels pull -p /path/to/kernel


- Submit to competition (assumes you've already signed up to the competiton and accepted the T&Cs)

        kaggle competitions submit -c [COMPETITION NAME] -f [FILE PATH]
