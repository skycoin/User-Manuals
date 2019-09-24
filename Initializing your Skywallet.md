# Initializing your Skywallet

After successfully checking that your Skywallet is genuine, you can begin with the initialization of your Skywallet.

## Step 1:

The first step in initializing your Skywallet is to install the Skycoin Desktop Wallet.

Please make sure to download the latest compatible version from the Skycoin [Downloads](https://www.skycoin.net/downloads/) Page.

If you already have the latest Desktop Wallet installed and configured, then you can skip this step.

## Step 2:

The next step is to download and install the daemon.

Following are the steps to install the daemon in different operating systems:

### Windows

* Download the daemon from the following link - []()

* You have to run the daemon every time you want to use the Skywallet.

### macOS

* Download the .pkg file from the following link - []()

* Double Click on the downloaded file and follow the instructions in the installer.

* Once completed, the daemon runs in the background, so you do not have to start it manually.

### Linux

* Open terminal on your Linux machine.

* Execute the following command using the terminal:  
*run wget -O /tmp/skyhwd.deb https://downloads.skycoin.net/skywallet-daemon/skyhwd_0.1.0_amd64.deb*

* After the process is complete execute the following command:  
*run dpkg -i /tmp/skyhwd.deb*

* Once completed, the daemon will run in the background.

## Step 3:

Connect your Skywallet to the USB port.

## Step 4:

Once you have connected the Skywallet to the USB port, open the Skycoin Desktop Wallet.

If it is the first time you are using your Skywallet, please make sure to go through the following section of the user manual,(Checking the Genuineness of your Skywallet)[https://github.com/skycoin/hardware-wallet/wiki/How-to-check-whether-device-is-genuine], to ensure that you are using a genuine Skywallet.

The instructions for a Desktop Wallet which is used for the first time and an already configured Desktop Wallet are different.

### Step 4.1: First Time Use of a Desktop Wallet

If you are using the Desktop Wallet for the first time, you will see the following screen :

<Screenshot of a Desktop Wallet which is used for the first time>

To configure your Skywallet, proceed to click on **“Using a hardware wallet?”** button.

Upon pressing the “Using a hardware wallet?” button, the display screen on your Skywallet will show a welcome message:

![Welcome_Message](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Skywallet%20Screen%20Mockup%20Edit_Skywallet%20Black_03.png)

To configure your Skywallet for the first time, you have to install the firmware for the Skywallet, as explained in [step #4](#Step_4).

### Step 4.2: Previously Configured Desktop Wallet

If you are **not** using your Desktop Wallet for the first time, then on connecting the Skywallet via USB, the following window will be displayed.

<Screenshot of a previously configured Desktop Wallet with other Wallets as well>

The window will display a list of all the Wallets that are already configured in your Desktop Wallet. (*Note - This may include both Hardware and Software Wallets*)

To configure your Skywallet click on the **“Hardware Wallet”** button.

On pressing “Hardware Wallet” button, the display screen on the Skywallet will show a welcome message:

![Welcome_Message](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Skywallet%20Screen%20Mockup%20Edit_Skywallet%20Black_03.png)

Once the welcome message is displayed on the Skywallet screen, you can proceed to install the firmware.

## Step 5: Installing the Firmware

To indicate the beginning of the firmware installation, the Desktop Wallet will show the following window:

<Screenshot of the Desktop Wallet showing the message about the installation of the firmware>

You can click on continue to start installing the firmware for your Skywallet.

The installation process will take a few seconds to complete. 

Once the installation is complete, you can proceed to configure the Skywallet.

**Note - If the installation process gets abruptly terminated for any reasons, you can disconnect the Skywallet, close the Desktop Wallet and then restart the whole process from the start.**

## Step 6: Skywallet Configuration

Once the firmware installation is complete, the “NEEDS SEED!” message is displayed by the Skywallet.

Simultaneously, the following window will be displayed by the Desktop Wallet.

![Unconfigured_HW](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Personalization%20-%201.PNG)

In this window, you can select two options :

**“Configure automatically”**

**"Restore backup"**

### Step 6.1: Configure automatically

If you are using a Skywallet for the **first** time, then you can proceed with the option of “Configure Automatically”.

“Configure automatically” button will configure your Skywallet as a new one.

Once the configuration is complete, the following window will be displayed.

<Screenshot of the configuration process completion>

You can use this window to change the name of your Skywallet. After which you can click on the “Close” button to close the window.

<Screenshot of a changed Skywallet name>

### Step 6.2: Restore backup

If you have already made a backup of a previously used Skywallet and need to restore it on the new Skywallet, then you can opt for the Restore Backup option.

The restoration process is explained in detail in this section - [Restore Configuration](https://github.com/skycoin/hardware-wallet/wiki/Restore-configuration)

If the Skywallet is **not** connected or not detected by your computer, then the following error message will be displayed:

<Screenshot of the error message showing no Skywallet detected>
