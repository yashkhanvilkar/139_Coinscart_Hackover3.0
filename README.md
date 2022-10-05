# 139_Coinscart_Hackover3.0
This is a repository for Hackover3.0

In this project we are creating a Lottery dApp on the matic testnet.

Stack used is as follows:</br>
<ul>
<li>Solidity for smart contract development,</li></br>
<li>Next.js for front-end development,</li></br>
<li>ThirdWeb to deploy and connect blockchain to front-end.</li></br>
</ul>

To run this app below are the steps: </br>
<ul>
<li>Clone this repository.</li></br>
<li>Go inside the backend folder, where you will find the contracts folder.</li></br>
<li>Inside of contracts folder is the Lottery.sol file.</li></br>
<li>Deploy the smart contract using npx thirdweb deploy command.</li></br>
<li>Now switch to lottery-dapp-frontend folder.</li></br>
<li>Run npm install.</li></br>
<li>Change the env file with your smart contract address(env should never be shared, this is just a demo).</li></br>
<li>Run npm run dev to check the dApp on your local server.</li></br>
</ul>
