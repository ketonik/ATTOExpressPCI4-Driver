# ATTOExpressPCI4-Driver
macOS driver for the ATTO Tech UL5D SCSI Host Adapter

ATTO Tech no longer has this driver for public download.
ATTO considers the UL5D obsolete thus wil nit support it.
That leaves us to be 'Renegades'.

The driver is provided here.

Instructions to install the driver were created based on Ventura. 

Most likely is required between Mojave to Ventura, prior to Mojave it most likely installs direct from the package.



sudo nvram boot-args="kext-dev-mode=1"

Reboot to Recovery,
Launch Terminal run: 

csrutil disable 

Check status: csrutil status

Install ATTOExpressPCI4.kext with Hackintool, approve it in System Settings and reboot.

LSI Logic 20320ie is PCIe apparently natively works no need drivers, not yet confirmed.
