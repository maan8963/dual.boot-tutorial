# Dual.boot-tutorial
This tutorial will help a beginner to learn about the process of installing and running two different operating systems on a single computer.
# 1. Overview
With a bootable Ubuntu USB stick, you can:

- Install or upgrade Ubuntu
- Test out the Ubuntu desktop experience without touching your PC configuration
- Boot into Ubuntu on a borrowed machine or from an internet cafe
- Use tools installed by default on the USB stick to repair or fix a broken configuration
  
This tutorial will show you how to create a bootable USB stick on Microsoft Windows using [Rufus](https://rufus.ie/en/)

Creating a bootable Ubuntu USB stick from Microsoft Windows is very simple and we’re going to cover the process in the next few steps.

# 2. Requirements
You will need:

- A 4GB or larger USB stick/flash drive
- Microsoft Windows XP or later
- [Rufus](https://rufus.ie/en/), a free and open source USB stick writing tool
- An Ubuntu ISO file. See [Get Ubuntu](https://ubuntu.com/download?_ga=2.250028994.53089604.1724431189-1971125994.1724431189) for download links

# 3. USB selection
Perform the following to configure your USB device in Rufus:

1. Launch Rufus
2. Insert your USB stick
3.  Rufus will update to set the device within the Device field
4. If the Device selected is incorrect (perhaps you have multiple USB storage devices), select the correct one from the device field’s drop-down menu

# 4. Select the Ubuntu ISO file
To select the Ubuntu ISO file you downloaded previously, click the **SELECT** to the right of “Boot selection”. If this is the only ISO file present in the Downloads folder you will only see one file listed.

Select the appropriate ISO file and click on **Open**.

# 5. Write the ISO
The Volume label will be updated to reflect the ISO selected.

Leave all other parameters with their default values and click **START** to initiate the write process.

# 6. Additional downloads
You may be alerted that Rufus requires additional files to complete writing the ISO. If this dialog box appears, select **Yes** to continue.


# 7. Write warnings
You will then be alerted that Rufus has detected that the Ubuntu ISO is an ISOHybrid image. This means the same image file can be used as the source for both a DVD and a USB stick without requiring conversion.

Keep Write in ISO Image mode selected and click on **OK** to continue.


Rufus will also warn you that all data on your selected USB device is about to be destroyed. This is a good moment to double check you’ve selected the correct device before clicking **OK** when you’re confident you have.


# 8. Writing the ISO
The ISO will now be written to your USB stick, and the progress bar in Rufus will give you some indication of where you are in the process. With a reasonably modern machine, this should take around 10 minutes. Total elapsed time is shown in the lower right corner of the Rufus window.


# 9. Installation complete
When Rufus has finished writing the USB device, the Status bar will be filled green and the word **READY** will appear in the center. Select **CLOSE** to complete the write process.

ubuntu-rufus-06
Congratulations! You now have Ubuntu on a USB stick, bootable and ready to go.

To use it you need to insert the stick into your target PC or laptop and reboot the device. It should recognise the installation media automatically during startup but you may need to hold down a specific key (usually F12) to bring up the boot menu and choose to boot from USB.


Finding help
If you get stuck, help is always at hand:

[Ask Ubuntu](https://askubuntu.com/?_ga=2.216024786.53089604.1724431189-1971125994.1724431189) 

[Ubuntu Forums](https://ubuntuforums.org/)

[IRC-based support](https://wiki.ubuntu.com/IRC/ChannelList?_ga=2.139997047.53089604.1724431189-1971125994.1724431189)

