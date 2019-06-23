# Safe-Storage
Blockchain to save files and check their existence

## Installation

```sh
$ git clone https://github.com/0x5eba/Safe-Storage.git
$ cd Safe-Storage
$ ./init.sh
```

## Guide step-by-step

To start the server `sudo -E ./Blockchain s` 

### Web Interface
1. Run `python website.py` for the web framework

2. Open `upload.html` in the browser

[![Demo]()](https://github.com/0x5eba/Safe-Storage/blob/master/Video/2019-06-21%2015-41-02.mp4)

### CLI
* To upload a file `./Blockchain c 1 path/file`

* To check if a file is stored the blockchain `./Blockchain c 2 path/file`
