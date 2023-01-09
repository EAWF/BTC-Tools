# Electrum Multisig Procedure
This is what I think we ALL need to do:

1. If you haven't already, download/install Electrum on the device that you want to use to manage this wallet.
2. Create a new 2of4 wallet and write down the mnemonic seed. Once that completes, an extended public key will be displayed. Save a copy for future use.
3. Send the extended public key(probably a zpub) to this group.
4. Shut down Electrum until you have received the other three extended public keys.
 5) Once step 4 is true, start Electrum and create a new 2of4 wallet.
 6) Use the "I have a seed" and type in the mnemonic seed received from step 2.
 7) Verify that the extended public key is the same as what you sent in step 3. If not, restart at Step 6.
 8) Add all three co-signers extended public keys to your wallet, which will result in a completed wallet which is ready to use.
 9) Go to the Receive Addresses and copy the first three to your clipboard.
10) Go to the Sign Message and use the three Receive addresses as the message.
11) Use the first address as the address to sign the message with.
12) Generate the signature and copy the signed message to your clipboard.
13) Send the signed message to this group.
14) As the others send their messages, verify each one and let the group know the results of the verification.
15) If all are verified, we're ready to use the wallet.
16) Send $5 in BTC from any wallet to the next empty receive address according to the wallet.
17) Everyone should verify that the funds are showing up in all of our wallets.
18) At the February meeting we should create a spending transaction to send $5 to one of our wallets.

As another means of testing, there should now be a way to export an account-level extended public key from the wallet which should be able to be used at: https://eawf.com/buidl.html in the fromXpub(xpub, change, index) section. Paste the extended public key into the xpub/ypub/zpub area, and by using the Index to 0, you should see the first address, 1, the second address, and 2, the third address in the wallet, etc.
