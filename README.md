# Cryptocurrency trading platform

Retrives data using poloniex api.

### Availble:
* Control trading sessinon via Start and Stop buttons.
* Real time interactive chart with trading strategy executions.
* Real time updating table with opened postions and all trades.
* Trading history storing into csv file.
* Real time messages from exchange and from platform in console.

Easy to change trading logic, avaialable different markets indicators to use in strategy module.
For using neccesary to have your own id and keu froim poloniex api.

## Install latest release:
Python:
```
pip install https://github.com/s4w3d0ff/python-poloniex/archive/v0.4.7.zip
```
## Usage:
```
import poloniex
polo = poloniex.Poloniex('your-Api-Key-Here-xxxx','yourSecretKeyHere123456789')
```
Neccessary packages: pandas, numpy, crayons, colorama, tkinter, matplotlib
![alt text](https://user-images.githubusercontent.com/10981310/35833395-b5d65d48-0ad9-11e8-821b-5416d9e04893.PNG)
