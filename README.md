
Cacti templates for ePMP
========================

# General(available for both AP and STA)

* CPU Utilization	
* Ethernet Errors/Drops
* Ethernet Traffic
* Ethernet Unicast Packets
* MCS DL Stats(Show the amount of packets sent on different MCS)
* MCS UL Stats
* Radio Errors/Capacity Drops
* Radio Retransmit Packets
* Radio Traffic

# Only for STA.

* MCS Modes(UP Link and Downlink MCS)
* STA Wireless Levels(RSSI and SNR)

# Installation

* Copy ePMP.xml and ePMP-radio-STA.xml to "<path_cacti>/resource/snmp_queries/"
* Import cacti_data_query_epmp_-_general_statistics.xml and cacti_data_query_epmp_-_sta_radio_stats.xml
* Add ePMP unit with SNMP v2(other versions will not work)
* Add "Associated Data Query" to ePMP device
* Add new graph via "New Graph" Menu checking "0" Index

# Screenshots

* AP Screenshot
![AP](https://github.com/m0sia/cacti-ePMP/raw/master/images/AP.png)

* STA Screenshot
![STA](https://github.com/m0sia/cacti-ePMP/raw/master/images/STA.png)

* MCS Stats
![MCS](https://github.com/m0sia/cacti-ePMP/raw/master/images/MCS Stats.png)

* Add new graph
![MCS Stats](https://github.com/m0sia/cacti-ePMP/raw/master/images/Add Graph.png)