# BTS-power-density

The energy consumption of base transceiver stations (BTS) for the reported mobile data usage are calculated over the years for different Radio Access Technologies (RAT’s), 3G, 4G and 5G respectively. Simulation can be runfor dense and sub urban areas, rural area is not investigated as a typical rural area is difficult to define due to low population and coarse BTS coverage.

## 1. Uncertainty simulation input parameters

### 1.1. Parameter Taxonomy

Parameter | Example Value | Uncertainty | Description
-------|---------|---------|---------
D | 3539000000 | -20% to 70% | consumed data in GB in the network -20% to +70% unsymmetric uncertainty 
X_3G | 0.07 | 2% units | share of 3G RAT in a network 2% units uncertainty
X_5G | 0.3 | 2% units | share of 5G RAT in a network 2% units uncertainty
E_3G | 2.24 | 20% | Energy consumption per 3G data symmertric uncertainty 20% 
E_4G | 0.0832 | 20% | Energy consumption per 4G data symmetric uncertainty 20% 
E_5G | 0.00832 | 20% | Energy consumption per 5G data symmetric uncertainty 20%
sub | 8870000 | 5% | number of total subscriptions symmetric uncertainty 5%
users | 3127 | 25% | users in the DU area symmetric uncertainty 25% 
n_Radio | 8 | 2 | Number of radios 
n_BB | 9 | 2 | Number of baseband
X_Radio | 520 | 100 | Electricity consumption of radio in Watt 
X_Baseband | 102 | 50 | Electricity consumption of baseband in Watt 
X_Data | 0.25 | 0.1 | Data share of selected site 
X_Marketshare | 0.31 | 0.05 | Marketshare of operator
