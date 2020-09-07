# Extreme Management Center DeviceView for Nokia SAR
>Community maintained content

The DeviceView does use reports in the MyReports directory. Those reports use FlexViews, FlexViews does use MIBs.

1. Make sure all flexviews are working. If not check relevant mibs are imported.
2. Upload reports to the `appdata/OneView/MyReports` directory.
3. Reports -> Reports -> Refresh.

## XMC 8.1.4

Product Family needs to be configured as Nokia Service Router

| Product  | DeviceView   | FlexView   |  Example  |
| -------- | ------------ |:----------:| --------- |
| Nokia Service Router |[Hardware](xml/DeviceViewNokiaHardware.xml?raw=true)|Nokia_ChassisInfo, Nokia_FanInfo, Nokia_PowerInfo, Nokia_SysInfo|[png](sample/Hardware.PNG?raw=true)|
| Nokia Service Router |[Interface](xml/DeviceViewNokiaInterface.xml?raw=true)|Nokia_VRinterfaces, Nokia_ISISinfo|[png](sample/Interface.PNG?raw=true)|
| Nokia Service Router |[LSP](xml/DeviceViewNokiaLSP.xml?raw=true)|Nokia_LSPinfo|[png](sample/LSP.PNG?raw=true)|
| Nokia Service Router |[RSVP](xml/DeviceViewNokiaRSVP.xml?raw=true)|Nokia_RSVPinfo|[png](sample/RSVP.PNG?raw=true)|
| Nokia Service Router |[SAP](xml/DeviceViewNokiaSAP.xml?raw=true)|Nokia_SAPinfo|[png](sample/SAP.PNG?raw=true)|
| Nokia Service Router |[SDP](xml/DeviceViewNokiaSDP.xml?raw=true)|Nokia_SDPinfo|[png](sample/SDP.PNG?raw=true)|
| Nokia Service Router |[Service](xml/DeviceViewNokiaService.xml?raw=true)|Nokia_svcbase|[png](sample/Services.PNG?raw=true)|
| Nokia Service Router |[System](xml/DeviceViewNokiaSystem.xml?raw=true)|Nokia_HWInfo,Nokia_BofInfo|[png](sample/System.PNG?raw=true)|

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