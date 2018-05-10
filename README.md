# `pandas` talk

### A presentation on `pandas` given to the Madison Python Meetup Group on May 10, 2018.

To convert the notebook file into slides:

```
sudo apt-get install -y python3
pip install ipython
ip_address=$(curl ifconfig.me)
jupyter nbconvert pandas_talk.ipynb \
    --to slides \
    --post serve \
    --ServePostProcessor.port=53703 \
    --ServePostProcessor.ip="${ip_address}"
```

Some requirements to run the notebooks:

```
sudo apt-get install -y python3 python3-lxml
python3 -m pip install pandas
python3 -m pip install bs4
python3 -m pip install html5lib
python3 -m pip install ipython
python3 -m pip install lxml
python3 -m pip install matplotlib
python3 -m pip install requests
python3 -m pip install scipy
```
