# Electrum Multisig Procedure
* Determine how many co-signor wallets will be able to sign a transaction(Y). This is the group.
* Determine how many co-signor wallets will be required to sign a transaction(X).

## Install Procedure for **each** Co-Signor:
1. Download and install the latest version of Electrum on the device that you want to use to manage this wallet.
2. Create a new X of Y wallet and create a new seed. 
3. Write down the mnemonic seed, then verify your seed.
4. Hit next and a Master Extended Public Key will be displayed.
5. Copy your Master Extended Public Key and send it to your group. *(Save a copy for yourself. You'll need it in Step 7.)
6. Shut down Electrum
7. Store your mnemonic seed safely, but keep it close by for the next step.

## When you have received ALL of the Master Extended Public Keys from your group:
1. Start Electrum and create a new X of Y wallet.
2. Select "I have a seed" and type in the mnemonic seed you wrote down in step 3.
3. Verify the mnemonic and that the extended public key is the same as what you sent in step 3. If not, restart at Step 6 
\* Procedure is Verified to Here: RH 20230109 \*
4. Add all of the co-signers Master Extended Public Keys to your wallet, which will result in a completed wallet which is ready to use.
5. Go to the Receive Addresses and copy the first three to your clipboard.
6. Go to the Sign Message and use the three Receive addresses as the message.
7. Use the first address as the address to sign the message with.
8. Generate the signature and copy the signed message to your clipboard.
9. Send the signed message to this group.
10. As the others send their messages, verify each one and let the group know the results of the verification. *The signatures and addresses should match what you have.*
11. If all are verified, the wallet is ready for use.

## Receive Funds Into The Wallet
1. Everyone Send a small amount of BTC to the next empty receive address that your wallet shows. When all are complete, you should have Y addresses used.
2. Everyone should verify that the funds are showing up in all of the wallets.
3. Your HD Multisig wallet(s) is/are ready for use!

## Send Funds From The Wallet
1. WIP

## Testing with buidl.js(buidl.html)
1. Export an account level extended public key from the wallet.
2. Paste it into https://eawf.com/buidl.html in the **Bulk From Xpub/Ypub/Zpub** section.
3. Change the depth input field to 3 and hit the **Generate** button.
4. The three addresses derived should match exactly with the addresses in your wallet.
