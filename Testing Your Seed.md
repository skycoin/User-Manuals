# Testing Your Seed

Once you have made the backup of a Seed, this Seed can be used to access your Skywallet. 

**NOTE - The Seed generated for a Skywallet can only be used with a Skywallet. You cannot use this Seed in the Desktop Wallet.**

If you want to check, whether a Seed you have written down belongs to a given Skywallet, you can use the **Confirm Seed** button. This is a security procedure to check whether the backup has been successful.

The "Confirm Seed" button will not be available when you are using your Skywallet for the first time. Instead you will see the button **Create Backup**.

Once you have clicked on the **Create Backup** button on the Hardware Wallet window and completed the process of the Seed backup, "Create Backup" button will be replaced by the "Confirm Seed" button.

<Two Screenshots where the first one is the Hardware Wallet window highlighting Create Backup button and the second one of the same window but highlighting the button confirm seed>

In order to check whether a Seed belongs to a particular Skywallet, you have to connect your Skywallet first. 

***If you are connecting the Skywallet for the first time, please read the following manuals - [Initialization of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/Initialize-the-wallet-setting-up) and [Personalization of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/Getting-to-know-the-wallet) to understand how to initialize and personalize your Skywallet for its first time use.***

If you are seeing the "Confirm Seed" button on your Hardware Wallet window, then it means that you have already taken the backup of the Seed.

After clicking on the "Confirm Seed" button the Skywallet will ask you to enter the different words in your Seed.

**However, the sequence of these word positions will be in a random order.**

<Picture of the Skywallet asking the user to enter a word on a particular position and a screenshot of the Desktop Wallet with the window showing the simultaneous message to enter the particular word at that position>

<Optional picture may be to explain the random sequence by reusing the last image and screenshot along with the next message displayed by the Skywallet to enter another word in another position and its simultaneous Desktop Wallet screenshot>

Along with asking you to enter the words of the Seed at a particular position, **the Skywallet may ask you to enter random words which are not part of the Seed.**

**Both the random words and the random sequence are a security measure to ensure that a potential attacker who might have access to your computer does get neither the full seed nor the right sequence.**

Once this process is complete, the Desktop Wallet will confirm whether the Seed you have entered is the correct Seed for the connected Skywallet.

<Screenshot1 the Desktop Wallet showing that the Seed is of the connected Wallet>
<Screenshot2 the Desktop Wallet showing that the Seed is not of the connected Wallet>
