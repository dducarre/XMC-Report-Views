# Custom DeviceView

XIQ Site Engine and XMC version 8.0.4+ you may import/modify the Device View content. This repository is to be used for hosting custom Device Views. 

* [Brocade](Brocade/README.md)
* [Cisco Systems](Cisco/README.md)
* [Check Point](CheckPoint/README.md)
* [Delta](Delta/README.md)
* [EfficientIP](EfficientIP/README.md)
* [Extreme 200 series](FastPath/README.md)
* [Extreme XIQ/Aerohive](XIQ/README.md)
* [Extreme/Avaya VSP](VOSS/README.md)
* [Extreme Universal Switch Platform Running VOSS](VOSS/README.md)
* [Extreme Universal Switch Platform Running EXOS](EXOS/README.md)
* [Extreme SummitX](EXOS/README.md)
* [FortiGate](FortiGate/README.md)
* [FortiWLC](FortiWLC/README.md)
* [HPE devices](Aruba-HP/README.md)
* [Huawei](Huawei/README.md)
* [InfoBlox](InfoBlox/README.md)
* [Juniper switches](Juniper/README.md)
* [Nokia SAR](Nokia/README.md)
* [PaloAlto Firewalls](PaloAlto/README.md)
* [SonicWall Firewalls](SonicWall/README.md)
* [VMware ESXi](VMware/README.md)
* [Multi vendor](MultiVendor/README.md)

## How to import DeviceView to XIQ Site Engine - Extreme Management (NetSight)
The DeviceView does use reports in the MyReports directory. Those reports use FlexViews, FlexViews does use MIBs.

1. Make sure all flexviews are working. If not check relevant mibs are imported.
2. Upload the .xml file (DeviceView) to the `Install_path/Extreme_Networks/NetSight/appdata/OneView/MyReports`
   On majority of Linux installations it is `/usr/local/Extreme_Networks/NetSight/appdata/OneView/MyReports`
3. Reports -> Reports -> Refresh.

## Troubleshooting = most common issues
* MIBs are missing
* MIBs are there but servers was not restarted to read those mibs
* MIBS are there but in MyMibs what server is not using by default
* FlexView is missing
* FlexView is not working at all
* FlexView is not working in OneView 
* FlexView does have wrong name = does not match the definition in DeviceView
* Device family is not recognized or is wrong

>Be Extreme
