## Dependency
jupyter


## Mac + Python 3 + jupyter
```
$ sudo easy_install pip
$ pip install --upgrade virtualenv

$ sudo pip3 install jupyter

$ mkdir ~/tensorflow
$ virtualenv --system-site-packages -p python3 ~/tensorflow

$ . ~/tensorflow/bin/activate
(tensorflow)$ pip3 install --upgrade tensorflow 
(tensorflow)$ jupyter notebook


...
(tensorflow)$ deactivate
```


## Mac + Python 2 + jupyter
$ sudo easy_install pip
$ pip install --upgrade virtualenv

$ sudo pip install jupyter

$ mkdir ~/tensorflow
$ virtualenv --system-site-packages ~/tensorflow

$ . ~/tensorflow/bin/activate

(tensorflow)$ pip install --upgrade tensorflow 
(tensorflow)$ jupyter notebook

...
(tensorflow)$ deactivate