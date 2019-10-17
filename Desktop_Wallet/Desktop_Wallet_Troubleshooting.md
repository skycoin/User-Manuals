# Troubleshooting

Here are some of the most common issues you might encounter when using a Desktop Wallet and the best possible resolutions for troubleshooting these issues. 

If you do not find a resolution for your issue, make sure you contact the support team via - **[store.skycoin.com/pages/support](https://store.skycoin.com/pages/support)**.

## Recovering a Desktop Wallet

To Safeguard your coins, the recovery of your Desktop Wallet is critical in the following cases:

* Lost Wallet password.

* Lost Backup Seed.

### <a name="Lost_Wallet_pwd"></a> Lost Wallet Password

It is always essential to keep your Wallet encrypted under all circumstances. 

Hence, in an unfortunate event of you losing or forgetting the password of your Desktop Wallet, the following recovery steps need to be followed.

To recover a Wallet for which the password is lost you should have the backup Seed. You can learn more about your Seed and the recommended backup methods for securing your Seed from the following chapter:  
[Security Recommendations for your Desktop Wallet](https://github.com/SkycoinProject/User-Manuals/blob/master/Desktop_Wallet/Security%20Recommendations%20for%20your%20Desktop%20Wallet.md)

Before beginning with the recovery process, you have to choose whether you are loading your new Wallet in your existing Desktop or a different Desktop.

If you are using a new Desktop, where you do not have a Skycoin Desktop Wallet installed, then you should download the latest version of Desktop Wallet from the [Downloads](https://www.skycoin.com/downloads) page.

You can learn how to initialize a Desktop Wallet from the following chapter:  
[Setting up your Desktop Wallet](https://github.com/SkycoinProject/User-Manuals/blob/master/Desktop_Wallet/Desktop_Setting%20up%20your%20Desktop%20Wallet.md).

If you have the Desktop Wallet already installed and you have not loaded the Wallet, which you are restoring, on your new Desktop, then you can proceed to the [recovery process](#recovery_prcs).

However, **if you have previously loaded the said Wallet to your new Desktop or if you are using the same Desktop for the recovery process, then you are needed to delete the entry for the said Wallet from the Wallets folder.**  
***Else you will get an error that the Wallet you are trying to load is already loaded.***

**Removing the Wallet from Wallets folder**

* Click on the "triple bar" symbol on the top right corner and then click on the **Backup Wallet** button.

![Triple_Bar_Button](https://github.com/SkycoinProject/User-Manuals/blob/master/Pictures/Pictures_Desktop_Wallet_Manual/Triple_Bar_Button_Highlighted.png)

* The list of all the Wallets which is configured on your Desktop will be displayed, along with ".wlt" filename.

* Find out the Wallet which you wish to restore and get the ".wlt" filename.

* Open the Wallets folder by clicking on the **Show** tab from the menu.  
<Screenshot of the show tab>

* Once in the Wallets folder, open the ".wlt" file which you have found on step 3.

* The contents of the ".wlt" file will look something like this:

![Wallet_File_Content](https://github.com/SkycoinProject/User-Manuals/blob/master/Pictures/Pictures_Desktop_Wallet_Manual/Wallet_File_Content.png)

* You can check the "Label" to confirm the name of your Wallet.

* Once confirmed, you can go ahead and delete it. 

**Always ensure you are deleting the correct .wlt file, as the deletion of a wrong file will remove the Wallet from your Wallet list and can only be recovered using its Seed.**

Once you have completed these steps, you can proceed to the recovery process.

<a name="recovery_prcs"></a> **Wallet Recovery Steps**

**Step 1** -  Click on the "Load Wallet" button on the bottom of the window.

**Step 2** - Enter the following details in the next window.  
* Name of the Wallet.
* Backup Seed of the Wallet you want to recover.
* New Password to encrypt the Wallet.

![Load Wallet Window](https://github.com/SkycoinProject/User-Manuals/blob/master/Pictures/Pictures_Desktop_Wallet_Manual/Load_Wallet_Window.png)

**Step 3** - Once the above data is entered, you can click on the "Load" button, to load your Wallet.

### Lost Backup Seed

The Seed of a Wallet is its most important component. If you lose or someone steals the Seed of your Wallet, it is recommended that you connect with the support team immediately via the following link -  
**[store.skycoin.com/pages/support](https://store.skycoin.com/pages/support)**.

However, you can recover your lost Seed if you have the encryption password with you, by following these steps:

**Step 1** - Open your Desktop Wallet.

**Step 2** - Click on the "triple bar" symbol on the top right corner and then click on the **Backup Wallet** button.

![Triple_Bar_Button](https://github.com/SkycoinProject/User-Manuals/blob/master/Pictures/Pictures_Desktop_Wallet_Manual/Triple_Bar_Button_Highlighted.png)

**Step 3** - Upon clicking the 'Backup Wallet" button, a window with the list of all the Wallets configured using the Desktop Wallet will be displayed.  
Click on the **Show Seed** button at the right end against the name of the Wallet for which you wish to view the Seed.

![Show Seed Window](https://github.com/SkycoinProject/User-Manuals/blob/master/Pictures/Pictures_Desktop_Wallet_Manual/Desktop_Wallet_Show_Seed.png)

**Step 4** - You will be prompted to enter the encryption password, once entered click on **Proceed**.

**Step 5** - The Wallet window will be displayed in a dialogue box.

The following chapter deals with the methods for safeguarding your Seed -  
[Security Recommendations for your Desktop Wallet](https://github.com/SkycoinProject/User-Manuals/blob/master/Desktop_Wallet/Security%20Recommendations%20for%20your%20Desktop%20Wallet.md).

## Syncing Issues

When you have downloaded your Desktop Wallet, the first step the Wallet performs is the explorer synching.

For the first time use, the synching process will take some time as it needs to sync all the previous blocks on the explorer.  
However, during your subsequent use, it would not take that longer owing to the time interval between your Desktop Wallet use.

At times, this syncing operation might get stuck at a particular point.  
In such cases where you get a syncing issue or a Wallet not loading error, you can try out the following remedial measures:

* The first resolution you could try is to restart your Wallet as well as your computer.  
In most cases, the syncing issues get rectified after the restarting.

* One of the most common issues that cause non-syncing is a bad internet connection.  
Check the connection speed of your network, also try disconnecting and reconnecting to check if it resolves the issue.

* If all the above steps have failed, then **backup your Wallet** (to ensure the safety of your coins) and then uninstall and reinstall the Desktop Wallet.

* You can also try downloading the latest version of the Skycoin Desktop Wallet from the [Downloads](https://www.skycoin.com/downloads) page.

If none of these methods fix your issue, then try contacting the support team at - **[store.skycoin.com/pages/support](https://store.skycoin.com/pages/support)**.

## <a name="Wipe_Wlt_Files"></a> Wipe the Wallet Files

Every Wallet you create using your Desktop Wallet will have a file created in the **Wallets Folder** on your computer.  
All these files will have the extension ".wlt" and the content of the file will be the details of the Wallet like name, address, etc.

Under some circumstances like the one mentioned in the topic **[Lost Wallet Password](#Lost_Wallet_pwd)**, you might need to remove these files.  
**To prevent accidentally deleting and loss of coins, make sure you have a backup of the ".wlt" files or have the backup Seed for all these files, before removing any of the ".wlt" files.**

**Step 1** - Click on the "triple bar" symbol on the top right corner and then click on the **Backup Wallet** button.

![Triple_Bar_Button](https://github.com/SkycoinProject/User-Manuals/blob/master/Pictures/Pictures_Desktop_Wallet_Manual/Triple_Bar_Button_Highlighted.png)

**Step 2** - The list of all the Wallets which is configured on your Desktop will be displayed, along with ".wlt" filename.

**Step 3** - Find out the Wallet which you wish to restore and get the ".wlt" filename.

**Step 4** - Click on the **Show** button on the top pane.

**Step 5** - Click on the **Wallets Folder** button.

**Step 6** - This will open a folder on your computer with the ".wlt" files for all the Wallets created using your Desktop Wallet.

**Step 7** - You can open the file which you have found in step 3 using a text editor software and check the content to confirm the specific Wallet which you wish to delete.  
The name of the Wallet will be available against the keyword "Label".

**Step 8** - Once confirmed, delete the ".wlt" file.

**To prevent accidentally deleting and loss of coins, make sure you have a backup of the ".wlt" files or have the backup Seed for all these files, before removing any of the ".wlt" files.**

## Delete addresses

You cannot remove addresses from your Desktop Wallet, and this is a security precaution to make sure that you would not delete an address accidentally and lose your coins.  
However, you can hide the addresses which are empty by clicking on the drop-down button at the right end of your Wallet and clicking on the **Hide empty** button.  
You can click on the same button again to show this address.

Moreover, if you want to remove a Wallet from your list, you can opt to delete the ".wlt" file of the said Wallet from the Wallets folder.  
The steps for this is explained in the topic **[Wipe the Wallet Files](#Wipe_Wlt_Files)**.

## Unconfirmed Transactions or Pending Transactions

The architecture of Skycoin helps you to make swift transactions across addresses.

However, on rare occasions, a transaction may take longer to process. Such pending transactions are primarily due to some congestion in the blockchain network and would usually resolve itself if you wait for sufficient time.
