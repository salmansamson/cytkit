---
PartData:
    Specs:
        Item: PMT module
        Power supply: +5, 0, -5 V
        Bias voltage control: 0 -- 1 V
        Signal output: SMA connector
    Suppliers:
        Hamamatsu:
            PartNo: H10723-20
            Link: 'https://www.hamamatsu.com/us/en/product/optical-sensors/pmt/pmt-module/voltage-output-type/H10723-20.html'
---

# Photomultiplier tube module 

>i (For Cytkit 1S-1F only. Not required for Cytkit 2S-14F.)

The recommended PMT module is the Hamamatsu H10723-series which is a PMT packaged with an internal high voltage power supply, bias voltage control, and transimpedance amplifier to give a voltage output. 

The peak signal to noise ratio occurs at control voltage ~ 500 mV. 

The module can be set up with low noise laboratory power supplies to supply the +5/0/-5 V and control voltage. Alternatively, the latter can be set up on a potentiometer connected to a 1 V reference supplied by the module itself. See datasheet for recommended wiring.

![](https://www.hamamatsu.com/content/dam/hamamatsu-photonics/sites/images/02_ETD/PMT%20module/Voltage%20output%20type/e_h10723_pp_xx,0.jpg.thumb.252.252.jpg)