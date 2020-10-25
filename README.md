# Wifi_DCF_validation
An accurate analytical model for IEEE 802.11 WLAN operation based on Distributed Coordination Function (DCF) MAC for a single network with saturated nodes, was originally presented in the reputed work [<sup>1</sup>](#refer-anchor-1).

- 11ax Parameters:  

|   Slot time $\sigma$ (us)   |           9           |
|:---------------------------:|:---------------------:|
|          SIFS (us)          |           16          |
|          DIFS (us)          |           34          |
|       PHY Header (us)       | 4us  * 5 OFDM symbols |
| Upper Layer Headers (Bytes) |           36          |
|           ACK (Bytes)       |           14          |
|              R              |          1000         |
|          $CW_{min}$         |           15          |
|          $CW_{max}$         |          1023         |
|             $m$             |           6           |


<div id="refer-anchor-1"></div>

- [1] [Performance analysis of the IEEE 802.11 distributed coordination function](https://ieeexplore.ieee.org/abstract/document/840210?casa_token=nSYGco9hfh0AAAAA:RR-_JjfutGZsx7QC4_KXS-gO9l8qYnOGI77eM1ikiaHmFQdNmWyV2UGHvAXhGl3tJgopD_RX)

