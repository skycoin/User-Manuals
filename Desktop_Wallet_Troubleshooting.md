# Troubleshooting

Here are some of the most common issues you might encounter when using a Skywallet and the best possible resolutions for troubleshooting these issues. 

If you do not find a resolution for your issue, make sure you contact the support team via - **[store.skycoin.net/pages/support](store.skycoin.net/pages/support)**.

You can also send an email at **support@skycoin.zendesk.com**.

## Recovering a Desktop Wallet

The recovery of your Desktop Wallet is critical in the following cases, to safeguard your coins:

* Lost Wallet password.

* Lost Backup Seed.

### <a name="Lost_Wallet_pwd"></a> Lost Wallet Password

It is always essential to keep your Wallet encrypted under all circumstances. 

However, in an unfortunate event of you losing or forgetting the password of your Desktop Wallet, the following recovery steps need to be followed.

To recover a Wallet for which the password is lost you should have the backup Seed. You can learn more about your Seed and the recommended backup methods in the following chapter:  
[Security Recommendations for your Desktop Wallet]()

Before beginning with the recovery process, you have to choose whether you are loading your new Wallet in your existing Desktop or a different Desktop.

If you are using a new Desktop, where you do not have a Skycoin Desktop Wallet installed, then you have to download the latest version of Desktop Wallet from the [Downloads](https://www.skycoin.net/downloads) page.

You can learn how to initialize a Desktop Wallet in the following chapter:  
[Setting up your Desktop Wallet]().

If you have the Desktop Wallet already installed and you have not loaded the Wallet which you are restoring in your new Desktop, then you can proceed to the below steps of the recovery process.

However, **if you have previously loaded the said Wallet to your new Desktop or if you are using the same Desktop for the recovery process, then you are needed to delete the entry for the said Wallet from the Wallets folder.**

**Removing the Wallet from Wallets folder**

* Open the Wallets folder by clicking on the **Show** tab on the top pane.  
<Screenshot of the show tab>

* Once in the Wallets folder, open each ".wlt" files to check which is the Wallet file for the Wallet which you are about to recover.

* The contents of the ".wlt" file will look something like this:

![Wallet_File](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Desktop_Troubleshooting%202.PNG)

* You can check the "Label" to know the name of your Wallet.

* Once the ".wlt" file is determined, you can go ahead and delete it. 

**Always ensure you are deleting the correct .wlt file, as the deletion of a wrong file will remove the Wallet from your Wallet list and can only be recovered using its Seed.**

**Wallet Recovery Steps**

Once you have completed the previous steps, you can proceed to the recovery process.

**Step 1** -  Click on the "Load Wallet" button on the bottom of the window.

**Step 2** - Enter the following details in the next window.  
* Name of the Wallet.
* Backup Seed of the Wallet you want to recover.
* New Password to encrypt the Wallet.

![Load Wallet Window](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Desktop_Troubleshooting%203_edit.PNG)

**Step 3** - Once the above data is entered, you can click on the "Load" button, to load your Wallet.

### Lost Backup Seed

The Seed of a Wallet is its most important component. If you lose or someone steals the Seed of your Wallet, it is recommended that you connect with the support team via the following methods -  
**[store.skycoin.net/pages/support](store.skycoin.net/pages/support)**.  
You can also send an email at **support@skycoin.zendesk.com**.

However, you can recover your lost Seed if you have the encryption password with you, by following these steps:

**Step 1** - Open your Desktop Wallet.

**Step 2** - Click on the "triple bar" symbol on the top right corner and then click on the **Backup Wallet** button.

![Show Seed](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Desktop_Troubleshooting%204.PNG)

**Step 3** - Upon clicking the 'Backup Wallet" button, a window with the list of all the Wallets configured using the Desktop Wallet will be displayed.  
Click on the **Show Seed** button at the right end against the name of the Wallet for which you wish to view the Seed.

![Show Seed Window](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Desktop_Troubleshooting%205.PNG)

**Step 4** - You will be prompted to enter the encryption password, once entered click on **Proceed**.

**Step 5** - The Wallet window will be displayed in a dialogue box.

To learn more about how to keep your Seed, please go through the following chapter - [Security Recommendations for your Desktop Wallet]().

## Syncing Issues

When you have downloaded your Desktop Wallet, the first step the Wallet performs is the explorer synching.

For the first time use, the synching process will take some time as it needs to sync all the blocks in the explorer.  
However, during your subsequent use, it would not take that longer owing to the time interval between your Desktop Wallet use.

At times, this syncing operation might not complete due to some reason.  
So in case if you get a syncing issue or a Wallet not loading error, you can follow these steps:

**Step 1** - The first step you could try is restarting your Wallet or your computer.  
Usually, the syncing issue will be rectified by either of these two methods.

**Step 2** - One of the most common issues that cause non-syncing is a bad internet connection.  
Check the connection speed of your network, also try disconnecting and reconnecting to check if it resolves the issue.

**Step 3** - If all the above steps have failed, then backup your Wallet, to ensure the safety of your coins, and then reinstall the Wallet.

**Step 4** - Finally, if all the above steps fail, then try downloading the latest version of the Skycoin Desktop Wallet from the [Downloads](https://www.skycoin.net/downloads) page.

## <a name="Wipe_Wlt_Files"></a> Wipe the Wallet Files

Every Wallet you create using your Desktop Wallet will have a file created in the **Wallets Folder** of your computer.  
All these files will have the extension ".wlt" and the content of the file will be the details of the Wallet like name, address, etc.

Under some circumstances like the one mentioned in the topic **[Lost Wallet Password](#Lost_Wallet_pwd)**, you might need to remove these files, to do you can follow these steps.  
However, **before removing any of the ".wlt" files, make sure you backup these files or have the backup Seed for all these files.**

**Step 1** - Open your Desktop Wallet.

**Step 2** - Click on the **Show** button on the top pane.

**Step 3** - Click on the **Wallets Folder** button.

**Step 4** - This will open a folder on your computer with the ".wlt" files for all the Wallets created using your Desktop Wallet.

**Step 5** - You can open each Wallet using a text editor software and check the content to get a specific Wallet.  
The name of the Wallet will be available against the keyword "Label".

## Delete addresses

You cannot remove addresses from your Desktop Wallet, and this is a security precaution to make sure that you would not delete an address accidentally and lose your coins.  
However, you can hide the addresses which are empty by clicking on the drop-down button at the right end of your Wallet and clicking on the **Hide empty** button. You can click on the same button to show this address.

Also if you want to remove a Wallet from your list, you can opt to delete the ".wlt" file of the said Wallet from the Wallets folder.  
The steps for this is explained in the topic **[Wipe the Wallet Files](#Wipe_Wlt_Files)**.

## Unconfirmed Transactions or Pending Transactions

The architecture of Skycoin helps you to make swift transactions across addresses.  
However, on rare occasions, a transaction may take longer to process.  
Such pending transactions are primarily due to some congestion in the blockchain and would usually resolve itself if you wait for sufficient time.
