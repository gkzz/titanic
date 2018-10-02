# titanic
I challenge Prediction Competition of Titanic: Machine Learning from Disaster with some references.

https://www.kaggle.com/c/titanic

i) "Titanic Data Science Solutions", by Manav Sehgal

https://www.kaggle.com/startupsci/titanic-data-science-solutions


ii) "An Interactive Data Science Tutorial", by Helge Bjorland

https://www.kaggle.com/helgejo/an-interactive-data-science-tutorial

iii) "新米データサイエンティストが覚えたての知識を使ってKaggleのタイタニックデータを分析し、投稿してみた！", @s_yaginuma from Qiita

https://qiita.com/s_yaginuma/items/4fa07cd1cde519a7e3d4


## Models I used

'Support Vector Machines', 

'KNN', 

'Logistic Regression',

'Random Forest', 

'Naive Bayes', 

'Perceptron', 

'Stochastic Gradient Decent', 

'Linear SVC', 

'Decision Tree'


## How to setup??

### move to titanic directory
cd /xxx/titanic

### make "output" directory
mkdir output

### type these commands before you install install necessary packages.
pip install --upgrade pip

sudo apt-get update

sudo apt-get upgrade

#### if you got the error as bellow;
Errors were encountered while processing:
/var/cache/apt/archives/libpython3.6-stdlib_3.6.5-5~16.04.york1_amd64.deb
E: Sub-process /usr/bin/dpkg returned an error code (1)
#### try to type this command
sudo dpkg --install --force all /var/cache/apt/archives/libpython3.6-stdlib_3.6.5-5~16.04.york1_amd64.deb
#### sources
https://askubuntu.com/questions/1037528/apt-get-upgrade-error-for-python-packages-in-ubuntu-16-04

### create python virtual environment
python -m venv <x: name of virtual environment ex) python version>

### move into python virtual environment
source x/bin/activate

### install all libraries that are needed in order to run this program
pip install -r requirements.txt

jupyter notebook

## Notes
python --version

Python 3.6.5

## If you face trouble...
plz give me comments!

