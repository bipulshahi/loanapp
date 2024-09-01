# install virtual environment
python -m pip install virtualenv

# check version
virtual --version

# create virtual environmet
virtualenv ml_package1

virtualenv ml_package2

# activate
# Linux/Mac => 
source ml_package1/bin/activate

# windows 
ml_package1\Scripts\activate
ml_package2\Scripts\activate

# change folder location where requirements.txt stored
D:
cd D:\Packaging-ML-Model\packaging_ml_model

# install requiremnts.txt
pip install -r requirements.txt

python training pipeline.py

python setup.py sdist bdist_wheel
