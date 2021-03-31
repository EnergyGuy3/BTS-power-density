# BTS-power-density

The energy consumption of base transceiver stations (BTS) for the reported mobile data usage are calculated over the years for different Radio Access Technologies (RAT’s), 3G, 4G and 5G respectively. Simulation can be runfor dense and sub urban areas, rural area is not investigated as a typical rural area is difficult to define due to low population and coarse BTS coverage.

## 3. Uncertainty simulation input parameters

### 3.1. Parameter Taxonomy

Parameter | Example Value | Uncertainty | Description
-------|---------|---------|---------
D | 140 | -20% to 70% | consumed data in GB in the network -20% to +70% unsymmetric uncertainty 
X_3G | 146.65 | 2% units | share of 3G RAT in a network 2% units uncertainty
X_5G | 162.06 | 2% units | share of 5G RAT in a network 2% units uncertainty
E_3G | 29.33 | 20% | Energy consumption per 3G data symmertric uncertainty 20% 
E_4G | 29.33 | 20% | Energy consumption per 4G data symmetric uncertainty 20% 
E_5G | 29.33 | 20% | Energy consumption per 5G data symmetric uncertainty 20%
sub | 29.33 | 5% | number of total subscriptions symmetric uncertainty 5%
users | 29.33 | 25% | users in the DU area symmetric uncertainty 25% 
users | 29.33 | 50% | users in the SU area symmetric uncertainty 50% 
