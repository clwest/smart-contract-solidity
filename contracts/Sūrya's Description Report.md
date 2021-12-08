 Sūrya's Description Report

 Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| /Users/chris/Desktop/development/smart-contract-lottery/contracts/Lottery.sol | e6bac7b2077293ff90d091830c9643404ffca99f |


 Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **Lottery** | Implementation | VRFConsumerBase, Ownable |||
| └ | <Constructor> | Public ❗️ | 🛑  | VRFConsumerBase |
| └ | enter | Public ❗️ |  💵 |NO❗️ |
| └ | getEntranceFee | Public ❗️ |   |NO❗️ |
| └ | startLottery | Public ❗️ | 🛑  | onlyOwner |
| └ | endLottery | Public ❗️ | 🛑  | onlyOwner |
| └ | fulfillRandomness | Internal 🔒 | 🛑  | |


 Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
