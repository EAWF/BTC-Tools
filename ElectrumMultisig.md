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
### Transaction Orignater(Sender)
1. One co-signor creates transaction from BTC Address from Receiver's Wallet, amount, and decides on the fee.
2. Click [Pay] button.
3. Click [Finalize] button.
4. Click [Sign] button.
5. Click [Export] button and send the transaction text to the rest of your group for signing.

### Transaction Signor(Co-signor)
1. Receive the transaction text and copy to your clipboard.
2. Work In Progress.


## Notes:
* You cannot sign a message with an address from a Multisig wallet because the actual private key is a conglomeration of keys.
* Your wallet type MUST be the same as all of the other wallet types.
  * If you use xPrv, all of the rest of the Extended Public Keys MUST be xPub. Same for yPrv or zPrv.
* Electrum 4.3.3 ONLY creates zPubs.
* Trezor One ONLY creates zPubs.
* If you want to use xPubs, then create an account in a wallet like Mycelium and export the xPrv and xPub, then create a new Electrum x of y, use the xPrv, and match the xPub to be shared.  
