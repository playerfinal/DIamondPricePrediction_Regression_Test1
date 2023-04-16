## Base Environment setup for ML project

#### Start by creating a VENV Environment
```
conda create -p venv environment
```
#### Now activate the environment
```
conda activate venv/
```
#### Now install library
```
pip install -r requirements.txt
```
##### In the end of requirements file add '-e .' 
##### '-e .' from reqirements.txt will trigger the setup.py
#### Then we configure setup.py
#### if you want to independetly trigger setup.py
```
python setup.py install
```