# ssb_advance_xml

● ssb_advance_xml: https://dustinchen26.github.io/ssb_advance_xml

● ssb_advance: https://dustinchen26.github.io/ssb_calculator_advance

● ssb_xml: https://dustinchen26.github.io/ssb_xml

● ssb_xml: https://dustinchen26.github.io/ssb_calculate

## example
```
Please enter the following parameters:
(band, carrierBw(RB), carrier_freq_low, carrier_freq_high, offsetToCarrier, coreset0numRB, coreset0offsetRB)
= ( 78, 273, 3603840, 3603840, 0, 48, 12)
= ( 48, 106, 3624990, 3624990, 102, 24, 2) // ref 38 508-1 Table 4.3.1.1.1.48-2 n48 and SCS 30 kHz
= ( 79, 273, 4849860, 4849860, 0, 48, 0)
= ( 41, 273, 2565750, 2565750, 0, 48, 12)
band: 78
carrierBw(RB): 273
carrier_freq_low: 3603840
carrier_freq_high: 3603840
offsetToCarrier: 0
coreset0RB: 48
coreset0offset: 12

Calculate
gscn=7890, absFreqPointA=3554700, absArfcnPointA=636980, absFreqSsb=3563040, absArfcnSsb=637536, dlEarfcn=640256, nDlCenterFreq=3603840, Kssb=4, offsetToPointA=26
                 <dlBwpCfg>
                    <mu>KHz30</mu>
                    <numRb>273</numRb>
                 </dlBwpCfg>
                 <dlFreqInfo>
                    <absFreqPointA>3554700</absFreqPointA>
                    <absArfcnPointA>636980</absArfcnPointA>
                    <absFreqSsb>3563040</absFreqSsb>
                    <absArfcnSsb>637536</absArfcnSsb>
                    <nrFreqBand>78</nrFreqBand>
                    <subCarrierCfg>
                       <offsetToCarrier>0</offsetToCarrier>
                       <subCarrierSpacing>KHz30</subCarrierSpacing>
                       <carrierBw>273</carrierBw>
                    </subCarrierCfg>
                    <bSChannelBwDL>100MHZ</bSChannelBwDL>
                    <dlEarfcn>640256</dlEarfcn>
                 </dlFreqInfo>  
                 <ulBwpCfg>
                    <mu>KHz30</mu>
                    <numRb>273</numRb>
                 </ulBwpCfg>
                 <ulFreqInfo>
                    <absFreqPointA>3554700</absFreqPointA>
                    <absArfcnPointA>636980</absArfcnPointA>
                    <nrFreqBand>78</nrFreqBand>
                    <subCarrierCfg>
                       <offsetToCarrier>0</offsetToCarrier>
                       <subCarrierSpacing>KHz30</subCarrierSpacing>
                       <carrierBw>273</carrierBw>
                    </subCarrierCfg>
                    <bSChannelBwUl>100MHZ</bSChannelBwUl>
                    <ulEarfcn>640256</ulEarfcn>
                 </ulFreqInfo>
                 <nDlCenterFreq>3603840</nDlCenterFreq>
                 <nUlCenterFreq>3603840</nUlCenterFreq>
                 <nDlBw>100</nDlBw>
                 <nUlBw>100</nUlBw>
...ˋetc

```
