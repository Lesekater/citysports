# Citysports to FTMS repeater
_fork of https://github.com/neelix2017/citysports_

This repeater presents itself as a standard FTMS treadmill and translates the [control values](./citysports.txt) of a Citysports treadmill into a generic BLE FTMS interface, so any FTMS-compatible app can talk to it.

## Running the Repeater
This repository is setup to be run with `uv`. To start:
- create a `.env` file by coping the `.env.example` file
- run `uv run citysports.py`

## Setup with pysetupdi
https://github.com/hbldh/bleak \
https://github.com/kevincar/bless \
https://github.com/gwangyi/pysetupdi

``python .\setup.py install``

## Credits
Thanks to: \
https://github.com/qhga/OpenEQiSports \
https://www.onelap.cn/pdf/FTMS_v1.0.pdf
