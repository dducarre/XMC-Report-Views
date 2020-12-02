# Extreme Management (NetSight) FlexViews for VOSS devices

Community Driven repository

## FlexViews
* [Port Configuration](tpl/VOSS_Port_Config.tpl?raw=true)
* [Fan Table](tpl/VOSS_FanTable.tpl?raw=true)
* [Chassis](tpl/VOSS_Chassis.tpl?raw=true)
* [ISid interface](tpl/VOSS_ISid_interface.tpl?raw=true)
* [ISid services](tpl/VOSS_ISid_Services.tpl?raw=true)
* [License](tpl/VOSS_License.tpl?raw=true)
* [Port Configuration Advanced](tpl/VOSS_Port_Advanced_Config.tpl?raw=true)
* [Port Vlan](tpl/VOSS_Port_Vlan_Table.tpl?raw=true)
* [Power Supply](tpl/VOSS_PowerSupply.tpl?raw=true)
* [Vlan table](tpl/VOSS_Vlan_Table.tpl?raw=true)
* [Line Cards](tpl/VOSS_Line_Cards.tpl?raw=true)
* [Is Config Saved?](tpl/VOSS_IsConfigSaved.tpl?raw=true)
* [PoE System](tpl/BOSS_VOSS_PoE_Main.tpl?raw=true)
* [PoE Ports](tpl/VOSS_PoE_Ports.tpl?raw=true)
* [VRRP basic](tpl/VOSS_VRRP_basic.tpl?raw=true)
* [VRRP advanced](tpl/VOSS_VRRP_advanced.tpl?raw=true)
* [FDB Local](tpl/VOSS_FDB.tpl?raw=true)
* [FDB Remote](tpl/VOSS_FDB_Remote.tpl?raw=true)



## Comments & Columns
##### Port Configuration
ifNamifName, ifDescr, ifOperStatus, rcPortType, rcPortAdminSpeed, rcPortAutoNegotiate, rcPortOperSpeed, rcPortAdminDuplex, rcPortOperDuplex

##### Fan Table
rcChasFanId, rcChasFanOperStatus, rcChasFanAmbientTemperature, rcChasFanType, rcChasFanFlowType

##### Chassis
rcChasType, rcChasSerialNumber, rcChasHardwareRevision, rcChasNumSlots, rcChasNumPorts

##### ISid interface
rcIsidInterfaceIfIndex, rcIsidInterfaceIsid, rcIsidInterfaceVlan, rcVlanName, rcIsidInterfaceCvid, rcIsidInterfaceType, rcIsidInterfaceOrigin, rcIsidInterfaceBpdu

##### ISid services
rcIsidServiceId, rcIsidServiceType, rcIsidServiceRowStatus, rcIsidServiceMaxMacLimit, rcIsidServiceMacLimitEnable, rcIsidServiceAction, rcIsidServiceOrigin, rcIsidServiceVnid, 

##### License
rcLicenseNumber, rcLicenseBitMap, rcLicenseFileName, rcLicenseLicenseType, rcLicenseDurationType, rcLicenseFactoryTrialPeriodRemainingDays, rcLicenseGenerationTime, rcLicenseExpirationTime

##### Port Configuration Advanced
rcPortIndex, ifName, ifDescr, ifOperStatus, rcPortLocked, rcPortNumStateTransition, rcPortVrfNameList, rcPortVrfCount, 

##### Port Vlan
rcVlanPortIndex, ifName, ifAdminStatus, ifOperStatus, ifDescr, ifAlias, rcVlanPortNumVlanIds,  rcVlanPortType, rcVlanPortDiscardTaggedFrames, rcVlanPortDiscardUntaggedFrames, rcVlanPortDefaultVlanId, 

##### Power Supply
Power Supply, Oper Status, PS Detail ID, Type, Serial Number, Part Number Description, Input Line Voltage

##### Vlan Table
rcVlanId, rcVlanStgId, rcVlanPlsbIsid, rcVlanType, rcVlanName, rcVlanColor, rcVlanVrfId, rcVlanRowStatus, rcVlanRmonEnable, rcVlanResult

##### Line Cards
Card Index, Card Type, Card Description, Admin status, Oper Status, Serial Number, HW Version, Part Number, Date Code, Daviations, Slot Power

##### Is Config Saved?
Name, Location, Config needs to be saved

##### PoE System
Unit-Slot, Nominal power, Oper Status, Consumption Power in Watt, Threshold percent

##### PoE Ports
Port, Description, PoE Enabled, PoE Status, PoE Priority, PoE Class, Power, Limit, Current, Voltage, Invalid Signatures, Denied, Over Loads, Short Counter

##### VRRP basic
Interface, Status, VRRID, VLAN, Virtual Mac, State, Priority, Primary IP, Master IP, Preempt, Backup Master, Backup Master State, Operations Control

##### VRRP advanced
Interface, Status, VRRID, VLAN, Virtual Mac, State, Priority, Primary IP, Master IP, Preempt, Accept, Backup Master, Backup Master State, Critical IP, Critical IP Enabled, Operations Control, Link Local Addr, HoldDown Timer, HoldDown State, HoldDown Time Remaining, Faster Adv Interval, Faster Adv Interval Enabled, Master Adv Interval

##### FDB Local
VlanID, MAC, Port, Status, BMac, Cvid

##### FDB Remote
VlanID, MAC, Status, Destination Address, Primary BVlan, Primary Destination, Primary Port, Secondary BVLAN, Secondary Desctination, Secondary Port

## Examples
* [Power Supply](sample/VOSS_PowerSupply.png?raw=true)
* [Line Cards](sample/VOSS_Line_Cards.png?raw=true)
* [Is Config Saved?](sample/VOSS_IsConfiSaved.png?raw=true)
* [PoE System](sample/BOSS_VOSS_PoE_Main.png?raw=true)
* [PoE Ports](sample/VOSS_PoE_Ports.png?raw=true)
* [VRRP basic](sample/VOSS_VRRP_basic.png?raw=true)
* [VRRP advanced](sample/VOSS_VRRP_advanced.png?raw=true)
* [FDB Local](sample/VOSS_FDB.png?raw=true)
* [FDB Remote](sample/VOSS_FDB_Remote.png?raw=true)


## MIBs
All necessary MIBs are included in the Extreme Management Center (NetSight) version 8.0.4 and newer.

>Be Extreme