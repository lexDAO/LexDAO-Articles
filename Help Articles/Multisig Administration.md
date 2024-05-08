# Acquiring IP Using multisig SAFE

```mermaid
timeline
  title Process to  acquire and register LexDAO IP assets
  section Monies approval
    Prior : submit proposal if > threshold_high or use petty cash discretion if < threshold_low 
    : {due process}
    : issued access to multisig wallet (with optional conditions)
    : document the wallet as Corrigenda to the grant proposal
  section Copyright (details below)
    Acquire Title : 1. identify NFT
        : 2. connect multisig wallet
        : 3. confirm and await threshold
    Acquire Waiver : look for commercial license (not personal use)
        : ask GC for tmp credit card
  section Digital Asset accounting
    Post Acquisition : add documentation to repo
        : special notes if bailor (physical item)
        : save license/waiver in ???folder
```

----
> [!WARNING]
> Because LexDAO is an organisation, you cannot use personal licenses/waivers for 3rd party imagery or graphics im articles
> Because audits are random, your sponsor must instruct you on the necessary procedures (it'd look silly for legal engineer to not engineer their own legals)

Use cases
1. Buying base NFT from OpenSea
2. Buying non-personnal-use graphics /tba/
3. ... ?

## Buying NFT from OpenSea
### Step 1 - Get the wallet connect link
[x] Go to OpenSea to the NFT you wish to purchase and enter the page for the NFT.  
[x] Click "login" at the top right corner.  
[ ] Select Wallet Connect from list.  When you do, a window with a QR code will appear.  
[ ] In the top right corner of that window will be a "copy" icon.  Click it to add to your clipboard.
![image](https://github.com/lexDAO/LexDAO-Articles/assets/14944510/555629c5-0d07-4f7a-ab08-8c024e991a56)

### Step 2 - Go to your SAFE account and log in
[x] Log into your SAFE (using addr given to you by GC or committee hat wearer)  
[x] click the dApp icon in the top menu bar.  It looks like a 'w'.  When you click this icon, 
[ ] a window will appear that shows an input field with the text 'wc' in the field.  
[ ] Paste the link from OpenSea into this bar and hit the "Paste" button. This should now show a connection to the NFT you were looking at.
![image](https://github.com/lexDAO/LexDAO-Articles/assets/14944510/5545971e-b30c-4aa5-97ef-7088ec9d26a9)

### Step 3 - Confirm the purchase
[ ] From within the SAFE Application main browser window a message will appear that asks for confirmation of your multisig connection to OpenSea.  
[ ] Sign it.  
[ ] If you require multiple signatures  in real-time it is **IMPORTANT** that this window will need to remain open until the threshold is met. 
[ ] Alternative if you require multiple signers, its best to batch up the send/receive transaction so that it gets signed async.
[ ] check the NFT finalisation via etherscan

### Step 4 - Catch typical errors /tbd/

> [!TIP]
> I'm not actually buying an NFT in this case so I cannot continue further down the purchase path, but I imagine it will be pretty straight forward from here.  If you need additional help, the flow from this point forward should look like this artice from [Safe's Knowledge Base](https://help.safe.global/en/articles/108235-how-to-connect-a-safe-to-a-dapp-using-walletconnect)

![image](https://github.com/lexDAO/LexDAO-Articles/assets/14944510/4fc5334f-7652-40cd-9e85-87f54f93c812)
<details><summary>connection rejected</summary><br>This is because the (Metamask) wallet you initially connected to STARTED on the wrong chain and SAFE is not smart enough to detect when you changed. Solution is to disconnect the wallet, make ure Metamask has the right network (Optimism) with the correct address assigned to the multisig, then reconnect</details>

<details><summary>connection request reset</summaryThere may be unsigned prior messages in the Metamask, make sure you sign the correct one by inspecting the message</details>

<details><summary>unsupported chain</summary>OpenSea supports (as of 2q2024) 8 chains</details>

<details><summary>wrong currency unit</summary>wETH as recipient token</details>

<details><summary>insufficient gas</summary><br> You need at least 1-2 cents to sign a transaction. This becomes a `lack of nail, battle / message / horse / shoe was lost` problem. Typically bridging takes >$15-20 which for 2 cents is overkill. Also despite documentation OP is not accepted as substitute, you require ETH. solution, get a mate to charity-drop a dollar or two to get started on the right chain (Optimism). Recommended action for onboarding OC new members is to airdrop $5 in gas (perhaps testnet facet) to get familiar with all the different (and UX complicated) tools. Note that Metamask charges nearly 1% in transaction fees so try and use something cheaper like Uniswap. 
</details>

![image](https://github.com/lexDAO/LexDAO-Articles/assets/14944510/6e7b7295-b091-4a3c-b268-d7ca2af77cf4)

### Step 5 - Debugging atypical errors

> [!WaRNING]
> Is there anomalous activity which may be a phishing attack?

![wallet connect]([https://platonnetwork.github.io/docs/en/assets/images/walletconnect-header-efbfd1fbd6de5bd770cf2f7e91d5cd7a.png](https://platonnetwork.github.io/docs/en/assets/images/establishing-connection-121e17f010e4b61a7995b823bd590327.png))
Look at the actual wallet connect [protocol](https://platonnetwork.github.io/docs/en/walletconnect_tutorial/) URI

`wc:84d75e28f2f6b0516ccfcf0979e99ff88d8aa24163d1f6a18333385e43311221@2?relay-protocol=irn&symKey=374557a4d0e58edbc27259202368f403c0994a15f65215ed4672ca77e46e67eb`

Missing cookies ... sometimes the site might be expecting secret session info which is not in your current window.

### Step 6 - RightClickSave

Let the mages [sort](https://docs.axelar.dev/dev/general-message-passing/overview) it out.
