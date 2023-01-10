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
2. Select "I have a seed" and type in the mnemonic seed you wrote down in step 3 above.
3. Verify the mnemonic and that the extended public key is the same as what you sent in step 5 above.
4. Add all of the co-signers Master Extended Public Keys to your wallet, which will result in a completed wallet which is ready to use.
5. STOP and **SECURE** your mnemonic seed ***AND*** your groups Master Extended Public Keys.
7. Go to the Addresses tab and copy the first address to your clipboard.
8. Send the address to your group.
9. The address sent from the others in your group should match what you have.
10. If all are verified, the wallet is ready to test with bitcoin.

## Receive Funds Into The Wallet
1. Everyone Send a small amount of BTC to the next empty receive address that your wallet shows. When all are complete, you should have Y addresses used.
2. Everyone should verify that the funds are showing up in all of the wallets.
3. Your HD Multisig wallet is ready for use!

## Send Funds From The Wallet
* WIP


## Notes:
* You cannot sign a message with a Bech32 Multisig wallet.
