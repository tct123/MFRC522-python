# joyit_mfrc522

A python library to read/write RFID tags via the MFRC522 RFID module.

This code was edited for the use with Raspberry Pi 5 by Joy-IT. The source code was published in relation to a [blog post](https://pimylifeup.com/raspberry-pi-rfid-rc522/) and you can find out more about how to hook up your MFRC reader to a Raspberry Pi there.

## Installation

This library is for the use with virtual environments for the Raspberry Pi 5 and older models.

```
mkdir your_project
python -m venv --system-site-packages env
source env/bin/activate

pip3 install spidev
git clone https://github.com/joy-it/MFRC522-python
cd MFRC522-python
python3 setup.py install
```
