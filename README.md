# asus-x556-uak-efi-configuration
A configuration of the EFI files for my Asus x556uak laptop

# Specs of the Laptop
Processor - i7-7500u (Kaby Lake)

RAM - 8 gig DDR4

Hard Drive - 256 gig, SSD

Graphics - Intel HD 620 (The NVIDIA drivers will not work beyond macOS High Sierra)

Realtek Audio


# What works

1. General - Battery, power, thermal management
2. Bluetooth
3. Trackpad - with the full range of gestures
4. Sound - with realtek alc fix
5. USB Ports as designed
6. Ethernet and USB tethering with HORNdiS
7. Onborad Intel HD 620 Graphics

# What DOESN'T work

1. WiFi (It is possible to purchase the broadcom chip to remedy this)




# How to use

While preparing your hackintosh usb, add these files to your efi partition and try booting from the USB stick. This EFI folder is designed to weork for the asus x556uak laptop, (F556U)m but should in general work for other kabylake laptops. The EFI folder comes with clover as well, so there's no need of a manual install. NVIDIA drivers for this laptop are also availbale, should you wish to use them.


As I have dealt extensively with the laptop in question, contact me at hackintosh@sumuk.me with your issue in the subject line and I'll be happy to assist you


Happy hackintoshing
