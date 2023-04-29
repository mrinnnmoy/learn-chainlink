<p>ChainLink</p>
<ul>
    <li>Chainlink  is a decentralized blockchain oracle network built on ethereum.</li>
    <li>The network is intended to be used to facilitate the transfer of tamper-proof data from off-chain sources to on-chain smart contract.</li>
</ul>

<p>What is an oracle?</p>
<ul>
    <li>Oracles are systems that can provide external data sources to ETH smart contracts.</li>
    <li>Ideally, oracles are systems that are trustless, meaning that they do not need to be trusted because they operate on decentralized principles.</li>
    <li>All oracles provide a few key functions, by definition.
        <li>Collect data from an on-chain source.</li>
        <li>Transfer the data on-chain with a signed message.</li>
        <li>Make the data available by putting it in a smart contracts's storage.</li>
    </li>
</ul>

<p>Types of Oracles.</p>
<ul>
    <li>Centralised Oracles.</li>
    <li>Decentralised Oracles.</li>
</ul>

<p>Smart contract to fetch BTC price using Chinalink Oracles.</p>
<ul>
    <li>The smart contract for fetching the price is written in "demo.sol", written in remix IDE and deployed using Metamask using Sepolia test network.
    </li>
</ul>

<p>Generate Random number using Chainlink oracles.</p>
<ul>
    <li>Step 1: Go to Chainlink docs.
        <a href="https://docs.chain.link/vrf/v2/subscription/examples/get-a-random-number" target="_blank">Click here.</a>
    </li>
    <li>
        Step 2: Create a Chainlink VRF subscription.
        <a href="https://vrf.chain.link/sepolia" target="_blank"></a>
    </li>
    <li>
        Step 3: Open remix IDE and write a contract written in the "randomNumber.sol".
    </li>
    <li>
        Step 4: Before deploying the contract, paste your VRF subscription ID to the "subscriptionID" function beside deploy button and then click deploy.
    </li>
    <li>
        Step 5: After successfully deploying, paste the contract address to the VRF subscription, consumer ID and then click on "requestRandom" function in remix IDE.
    </li>
    <li>
        Step 6: Then click on "lastRequestId" function and copy the ID, and paste it in the "getRequestStatus" function and see the status and random number generated.
    </li>
</ul>
