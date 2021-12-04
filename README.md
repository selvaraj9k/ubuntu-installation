# ubuntu-installation
### ubuntu installation in hardware
### How To Install Ubuntu: Run Linux On Your Laptop Or PC

**Ubuntu’s standard installation** method is to download the **ISO Disk Image File** and burn it to a **CD** or **DVD**. Still, Canonical is aware that many netbook, notebook, and laptop users may not have access to a CD/DVD drive and that a USB stick is often preferred by most users anyway. Therefore, you have both methods available to install Ubuntu.

![ubuntu](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/ubuntu.jpg)

# Prerequisites
- System requirements (recommended):
  - **2 GHz dual-core processor**
  - **4GB memory**
  - **25GB available disk space for storage (less if installing the minimal version)**
  - **DVD drive or USB port**
- At least a 4GB USB drive

![ubutnu-linux](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/ubuntu-linux.jpg)

# Download the Installation Media

In a web browser, visit the [Ubuntu download page](https://ubuntu.com/download) and pick a version suitable for your machine. The most popular versions include:
- [Ubuntu Desktop](https://ubuntu.com/download/desktop)
- [Ubuntu Server](https://ubuntu.com/download/server)
- [Ubuntu Derivatives](https://ubuntu.com/download/flavours)

Once you find the version you need, click the green **Download button**. You’ll be taken to a thank-you page, and your download should start. (We will download and install Ubuntu 20.04 for desktops.)

![ubuntu-1](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/ubuntu-1.png)

The download is an .iso file. You can use it to create a bootable USB drive.
Save the file to a location of your choice.

# Create Bootable USB Drive
## Create Bootable USB Drive on Linux
### BalenaEtcher

You’ll need to install a third-party utility called balenaEtcher to create a USB bootable drive.

Download the balenaEtcher utility. Scroll down to the download section and click the link to download the latest version of balenaEtcher.

Run the file once downloaded.And Extract and use it.

 The balenaEtcher utility launches. Plug in the USB drive – you should see the drive pop up in the device field.

- In the Flash from file, click Disk or ISO Image.
- Browse and select the .iso Ubuntu file you downloaded earlier.
- Select  Target USB as the device you wish to write to.
- Click the Flash button to the Flash.

![ubuntu-2](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/ubuntu-2.png)

### Make Startup Disk (Default in Ubuntu)

- In the Source disc image from file, click Disk or ISO Image.
- Browse and select the .iso Ubuntu file you downloaded earlier.
- Select  Target USB as the device you wish to write to.
- Click the Make Startup disk button to the Flash.
 
![ubuntu-3](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/ubuntu-3.png)

## Create Bootable USB Drive on Windows

You’ll need to install a third-party utility called Rufus to create a USB bootable drive.

- [Rufus](https://rufus.ie/en/)

Insert the **PenDrive**

![os_1](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_1.jpg)

# Boot from USB

Switch off your computer and remove all other USB devices (like printers, memory cards, etc.).

Insert the bootable USB and switch on the computer.

Next, one of two things will happen:

- The computer will automatically boot from the USB if our BIOS/UEFI is set up correctly.
- You need to set up boot from USB manually, through the Boot Menu or BIOS/UEFI.

## Boot USB from Boot Menu

As the computer is switching on, you can access the Boot Menu by pressing the correct key (or combination of keys). The keys that take you to the required menu depend on the brand of computer. This is the list of common keys based on the brand:




|     Brand   |    Keys         |
| ----------- | --------------- |
| Asus	      | F8 or Esc       |
| Acer        | F12, F9 or Esc  |
| Compaq      | F9 or Esc       |
| Dell        | F12             |
| eMachines   | F12             |
| Fujitsu     | F12             |
| HP          | F9 or Esc       |
| Lenovo      | F8, F10 or F12  |
| Samsung     | F2, F12 or Esc  |
| Toshiba     | F12             |

Once you have accessed the Boot Menu, select the USB as the device to boot from and press Enter.
If you are unable to boot from the USB this way, try doing it by opening BIOS/UEFI.


## Boot USB from BIOS/UEFI

Just as accessing the Boot Menu, to open the BIOS/EUFI you need to hit the correct keys that correspond to the computer brand. The list of common keys for accessing the BIOS/UEFI is:


|  Brand     |        Keys         |   
|----------- | ------------------- |
|Asus	     |  F9 or Del          |
|Acer        |	F2, F9 or Del      |
|Compaq      |	F10                |
|Dell	     |  F2                 |
|eMachines   | 	Tab or Del         |
|Fujitsu     |	F2                 |
|HP	     |  F10, F11 or Esc    |
|Lenovo	     |  F1 or F2           |
|Samsung     |	F2                 |
|Toshiba     |	F1, F2, F12 or Esc |


Once you access the BIOS/UEFI, find the Boot Device Select Menu and set the USB as first in the Boot Order. With this configuration in place, your computer will boot from the USB (if possible). If there is no bootable flash drive present, it will run the OS from the hard drive, as per usual.

Note: Make sure to disable legacy mode or secure boot, if your system has this option.




![os_2](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_2.jpg)
![os_3](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_3.jpg)
![os_4](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_4.jpg)
![os_5](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_5.jpg)
![os_6](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_6.jpg)
![os_7](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_7.jpg)
![os_8](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_8.jpg)
![os_9](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_9.jpg)
![os_10](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_10.jpg)
![os_11](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_11.jpg)
![os_12](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_12.jpg)
![os_13](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_13.jpg)
![os_14](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_14.jpg)
![os_15](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_15.jpg)
![os_16](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_16.jpg)
![os_17](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_17.jpg)
![os_18](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_18.jpg)
![os_19](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_19.jpg)
![os_20](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_20.jpg)
![os_21](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_21.jpg)
![os_22](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_22.jpg)
![os_23](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_23.jpg)
![os_24](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_24.jpg)
![os_25](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_25.jpg)
![os_26](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_26.jpg)
![os_27](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_27.jpg)
![os_28](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_28.jpg)
![os_29](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_29.jpg)
![os_30](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_30.jpg)
![os_31](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_31.jpg)
![os_32](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_32.jpg)
![os_33](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_33.jpg)
![os_34](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_34.jpg)
![os_35](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_35.jpg)
![os_36](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_36.jpg)
![os_37](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_37.jpg)
![os_38](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_38.jpg)
![os_39](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_39.jpg)
![os_40](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_40.jpg)
![os_41](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_41.jpg)
![os_42](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_42.jpg)
![os_43](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_43.jpg)
![os_44](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_44.jpg)
![os_45](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_45.jpg)
![os_46](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_46.jpg)
![os_47](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_47.jpg)
![os_48](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_48.png)
![os_49](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_49.png)

