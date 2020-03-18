# kaggle-covid

Kaggle competition for COVID-19.

Kaggle competition: https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge

White House call to action: https://www.whitehouse.gov/briefings-statements/call-action-tech-community-new-machine-readable-covid-19-dataset/


# Setup

1. `git clone https://github.com/kaggle-covid/kaggle-covid.git`
2. `cd kaggle-covid`
3. `mkvirtualenv --python=/usr/local/bin/python3 kaggle-covid`
4. `pip install -r requirements.txt`
5. Download the dataset (2GB) from https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge
6. `mv /path/to/CORD-19-research-challenge.zip ./data`
7. `cd ./data`
8. `unzip CORD-19-research-challenge.zip`