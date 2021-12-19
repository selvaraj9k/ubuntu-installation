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
- At least a **4GB USB drive**

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

- In the Flash from file, click **Disk** or **ISO Image**.
- Browse and select the .iso Ubuntu file you downloaded earlier.
- Select  Target USB as the device you wish to write to.
- Click the Flash button to the Flash.

![ubuntu-2](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/ubuntu-2.png)

### Make Startup Disk (Default in Ubuntu)

- In the Source disc image from file, click **Disk** or **ISO Image**.
- Browse and select the .iso Ubuntu file you downloaded earlier.
- Select  Target USB as the device you wish to write to.
- Click the Make Startup disk button to the Flash.

![ubuntu-3](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/ubuntu-3.png)

# WoeUSB Install

- [WoeUSB](https://github.com/selvaraj-kuppusamy/software_install/blob/main/WoeUSB_Install/Install_WoeUSB_in_Linux.bash)

![ubuntu-4](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/ubuntu-4.png)

## Create Bootable USB Drive on Windows

You’ll need to install a third-party utility called Rufus to create a USB bootable drive.

- [Rufus](https://rufus.ie/en/)

Insert the **PenDrive**

![os_1](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_1.jpg)

# Boot from USB

Switch off your computer and remove all other USB devices (like printers, memory cards, etc.).

Insert the **bootable USB** and switch on the computer.

Next, one of two things will happen:

- **The computer will automatically boot from the USB if our BIOS/UEFI is set up correctly**.
- **You need to set up boot from USB manually, through the Boot Menu or BIOS/UEFI**.

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
If you are unable to boot from the USB this way, try doing it by opening **BIOS/UEFI**.


## Boot USB from BIOS/UEFI

Just as accessing the Boot Menu, to open the **BIOS/EUFI** you need to hit the correct keys that correspond to the computer brand. The list of common keys for accessing the **BIOS/UEFI** is:


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


Once you access the **BIOS/UEFI**, find the Boot Device Select Menu and set the USB as first in the Boot Order. With this configuration in place, your computer will boot from the USB (if possible). If there is no bootable flash drive present, it will run the OS from the hard drive, as per usual.

Note: Make sure to disable legacy mode or secure boot, if your system has this option.

Note: If you have a dual boot machine, you can set up Ubuntu along with your existing operating system. In this case, you will need to select Something else and create the partitions.

Below Picture Showing My Laptop.

![os_2](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_2.jpg)

**BIOS** Information.

![os_3](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_3.jpg)

Go to **Boot Option**.

![os_4](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_4.jpg)

To Visible all the options.


![os_5](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_5.jpg)


In **Boot Priorty** Option , To change ***Legacy Support to UEFI first***.

![os_6](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_6.jpg)

Press **Esc Button**, It shows the **Exit** Saving Changes Message.
And Then Press yes to Save Changes

![os_7](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_7.jpg)

The **System** was On Within a Second.

![os_8](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_8.jpg)

Loaded  **GNU GRUB**. Press Ubuntu..


![os_9](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_9.jpg)

Now **Ubuntu Operting System** is Loading...


![os_10](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_10.jpg)

Now **Checking Disks**...

![os_11](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_11.jpg)


Check Finished. **Disks has No Errors**.


![os_12](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_12.jpg)

**Ubuntu** is Processing....

![os_13](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_13.jpg)

# Run Ubuntu
# Install Ubuntu 20.04 LTS Desktop

To begin the installation, click **Install Ubuntu**.

![os_14](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_14.jpg)

# Choose Keyboard Layout

**By default, the system will select English and English**.

If you have a non-standard keyboard, you can select it in the list. Alternately, click Detect Keyboard Layout and the system will automatically choose your keyboard. If you need to test your keyboard, use the labeled field.

When you’re ready, click **Continue**.


![os_15](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_15.jpg)

##  Network Connection
### Wireless Network Connection

There are two Options

- I don't want to connect to a **WiFi** network right now.
- Connect to this network.

![os_16](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_16.jpg)

Connect the Network.
To the Available **Wifi Network Connection**.

![os_17](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_17.jpg)


Select the **Wifi Network Connection**, and Enter the Password.


![os_18](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_18.jpg)

**Wireless Network Connection** was Conneted.

![os_19](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_19.jpg)


## Choose Starting Applications

- **Normal Installation –** This is the full Ubuntu Desktop experience, with office software, games, and media players.

- **Minimal Installation –** Choose this to save disk space, especially if you won’t be using media players or productivity software.

You’ll also be asked to confirm other options:

- **Download updates while installing Ubuntu –** This does the work of downloading large package files during the installation. Once the installation finishes, the packages will be ready to apply as updates.

- **Install third-party software for graphics and Wi-Fi hardware and additional media formats –** Some hardware, like graphics cards and wi-fi cards, do not have open-source driver support. Also, some media formats, such as .wmv, do not fall under the GPL license. If you need support for these, you’ll need to agree to additional terms of use.



![os_20](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_20.jpg)
![os_21](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_21.jpg)


# Disk Partitioning
Next, you’ll be presented with an Installation Type dialog. You can wipe the hard drive clean prior to installing Ubuntu by clicking Erase disk and install Ubuntu. If you go this route, skip ahead to the next step.

Advanced users may want to edit Advanced Features. Use this to specify your own disk partitions or set other advanced options:

- Use LVM with the new Ubuntu installation: LVM stands for Logical Volume Management. This is a tool for dynamically managing different virtual drives on your system. It’s much like an enhanced version of the gparted tool.
- Encrypt the new Ubuntu installation for security: This will encrypt the drive’s contents. You’ll choose a security key, which will be required to decrypt and use the drive.
- Experimental: Erase disk and use ZFS:  ZFS refers to Zettabyte File System, but it has grown into a hybrid file system and volume manager. Since it’s still being tested, avoid this setting on mission-critical production system

If you’d rather create your own hard drive partitions, click Something Else.

The next screen will allow you to create your own partition table and logical drives. This lets you divide a physical hard drive into different partitions. The operating system sees partitions as individual drives.

Note: Some users create their /home directory on a separate partition. If the operating system needs to be reinstalled, the partition with the /home directory is unaffected.

Click Continue to apply your changes to the drive partitions.

You’ll be asked to Write changes to disks?  None of the options you’ve selected are permanent until you click Continue on this screen.  Click Continue to proceed.



![os_22](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_22.jpg)

For this scenario, you need to set up partitions manually so choose **Something else** and **click Continue**.

![os_23](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_23.jpg)

For this scenario, ***Delete all the partitions***.

![os_24](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_24.jpg)
![os_25](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_25.jpg)

Now, the ***Disk is free***.
Now you need to partition your hard drive for the installation. Simply select/click on the unpartitioned storage device from the list of available storage devices. Then click New Partition Table.

![os_26](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_26.jpg)

Now you should be able to see the free space created equivalent to the **capacity of the hard drive**. Double click on the free space to create a partition as described next.


![os_27](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_27.jpg)


To create a **(/boot) partition** (where the base system files will be installed), enter the size of the new partition out of the total free space. Then set the file system type to **EXT4** and the mount point to ***/boot*** from the drop-down list.


![os_28](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_28.jpg)
![os_29](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_29.jpg)


To create a **root(/)  partition** (where the base system files will be installed), enter the size of the new partition out of the total free space. Then set the file system type to **EXT4** and the mount point to ***/*** from the drop-down list.


![os_30](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_30.jpg)
![os_31](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_31.jpg)
![os_32](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_32.jpg)


Next, create a **SWAP partition**. The swap partition is used as ***virtual memory*** in case your system runs out of the memory (RAM). For a system with a limited amount of RAM, the rule of thumb is to create the swap partition twice the size of the actual hardware RAM.


![os_33](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_33.jpg)
![os_34](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_34.jpg)

All done. Review the partitions and hit the **Install Now** button.

![os_35](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_35.jpg)

Next, click **Continue** from the pop-up window on the device.

![os_36](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_36.jpg)

Next, click **Continue** from the pop-up window on the device.

![os_37](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_37.jpg)


You will be prompted to permit the installer to write the recent changes concerning **partitioning to disk**. Click Continue to proceed.


![os_38](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_38.jpg)

changes to disks are processing...

![os_39](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_39.jpg)

# Select Time Zone
Once the system formats the **disk partitions**, the installer will ask Where are you?

Type the nearest large city into the box, and the system will set your **local time zone**.

Click Continue.

Note: It’s always possible to change the timezone on Ubuntu at a later point in time.


![os_40](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_40.jpg)

## Create User Account

Next, you’ll need to configure a user account. Fill in the following fields:

- **Name:** Your actual name.
- **Computer name:** This is the hostname or network name.
- **Username:** The user account name you want to use.
- **Password:** Enter and confirm a strong password – the installer will automatically evaluate your password strength.
- **Log in automatically:** This is not recommended for publicly accessible servers.
- **Require my password to log in:** This is recommended for publicly accessible servers.


Continue to **install Ubuntu**


![os_41](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_41.jpg)

**Ubuntu installation** is process.

![os_42](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_42.jpg)


**Ubuntu installation** is Processing...


![os_43](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_43.jpg)
![os_44](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_44.jpg)
![os_45](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_45.jpg)

Installation completed and **Restart** the System now.

![os_46](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_46.jpg)

**Remove the PenDrive** and Then press Enter.

![os_47](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_47.jpg)

Ubuntu **Desktop** view.

![os_48](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_48.png)


Checking **OS Version**.

![os_49](https://github.com/selvaraj-kuppusamy/ubuntu-installation/blob/main/assets/os_49.png)

# Conclusion

You should now have successfully installed Ubuntu 20.04 on your computer.


