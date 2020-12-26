# Xbox One controller on Windows 7
There's a somewhat helpful (but not completely helpful) [guide](https://steamcommunity.com/app/564050/discussions/0/1750106661703347732) on the steam forums. The guide indicates, as other pages do, that Microsoft has removed the pages on which they formerly offered device drivers for Xbox One controllers on Windows 7. As an alternative, the guide links to some unsigned drivers. However, searching on microsoft's own _update_ site will deliver a file that does the trick.

## Steps

1. Go to http://www.catalog.update.microsoft.com/Search.aspx?q=xbox%20one%20controller (Search for "xbox one controller" if it doesn't automatically perform the search.)
1. Download the search result described as indicated in the **Download Description** section below. (I just experimented with a couple of the search results until I found one that the OS would accept in the later steps.)
1. That should download the archive file [`20656929_ce9bb23845f18c7ed66d07d417969c567a61d223.cab`](http://download.windowsupdate.com/d/msdownload/update/driver/drvs/2014/06/20656929_ce9bb23845f18c7ed66d07d417969c567a61d223.cab). Extract its contents. One of the extracted files should be `xb1usb.inf`
1. Open Device Manager. (Press Windows/Super button. Type "Device Manager." Click same.)
1. Right-click the icon for the XB1 game controller (probably under **Other Devices > Controller**, which should have a small warning badge to indicate that it has no working driver assigned. Select **Properties**. Click **Update Driver**.
1. Select **Browse my computer for driver software**, then ** Let me pick from a list of devices on my computer**.
1. Highlight **Show All Devices**, then click **Next**
1. Click **Have Disk...**, then choose the extracted `xb1usb.inf` file (assuming all the files extracted from `20656929_ce9bb23845f18c7ed66d07d417969c567a61d223.cab` ended up in the same directory).

## Download Description

Title | Products | Classification | Last Updated | Version | Size
--- | --- | --- | --- | --- | ---
Microsoft - Other hardware - Microsoft Xbox One Controller (DFU) | Windows 10 and Later Servicing Drivers for testing,Windows 7,Windows 8.1 and later drivers | Drivers (Other Hardware) | 5/25/2014 | 6.2.11059.0 | 1.5 MB
