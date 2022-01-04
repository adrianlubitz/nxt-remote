# nxt-remote
A python remote for the LEGO NXT using [nxt-python](https://github.com/schodet/nxt-python). This project was developed using python 3.7 on Windows.

## Install
Follow the [install guide of nxt-python](https://github.com/schodet/nxt-python#requirements) and make sure to properly install *PyUSB* and *PyBluez*. 
I needed to put the **libusb-1.0.dll** in the *system32* folder to make *PyUSB* work.


## Usage
To start the remote just run

```bash
python remote.py
```

## Known Issues
The Bluetooth connection is not working with my setup of nxt-python under Windows.