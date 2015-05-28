```
_/\/\/\/\/\_________________________/\/\______/\/\_______________________
_/\/\____/\/\___/\/\/\_____/\/\/\/\_/\/\/\__/\/\/\___/\/\/\___/\/\/\/\___
_/\/\/\/\/\___/\/\/\/\/\_/\/\__/\/\_/\/\/\/\/\/\/\_/\/\__/\/\_/\/\__/\/\_
_/\/\__/\/\___/\/\_________/\/\/\/\_/\/\__/\__/\/\_/\/\__/\/\_/\/\__/\/\_
_/\/\____/\/\___/\/\/\/\_______/\/\_/\/\______/\/\___/\/\/\___/\/\__/\/\_
_________________________/\/\/\/\________________________________________
```
**...provides a measurement tool set for wireless research with Atheros WiFi hardware**

### This RegMon git repo includes:

- RegMon measurement tool provided as patches for ath5k, ath9k and madwifi Linux drivers in OpenWRT
- shell scripts to set up measurements on OpenWRT WiFi routers
- parser scripts (mainly AWK) to bring the raw RegMon data in proper shape to ananlyse with R
- R scripts to perform statistics and generate plots

### How to reference to  RegMon ?
Just use the following bibtex :
```
@PhdThesis{Huehn2013,
 author      = {Thomas H{\"u}hn},
 title       = {A Measurement-Based Joint Power and Rate Controller for IEEE 802.11 Networks},
 school      = {Technische Universit{\"a}t Berlin, FG INET Prof. Anja Feldmann},
 year        = 2013,
 month       = July,
 urn         = {urn:nbn:de:kobv:83-opus4-39397},
 url         = {http://opus4.kobv.de/opus4-tuberlin/frontdoor/index/index/docId/3939}
}
```
