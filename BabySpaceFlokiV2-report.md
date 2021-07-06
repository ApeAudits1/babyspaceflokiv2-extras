## Sūrya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| babyspaceflokiV2.sol | 9bd9dbfc5939ec5f89f1133993a21fb81e7c753e |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **IERC20** | Interface |  |||
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
||||||
| **IERC20Metadata** | Interface | IERC20 |||
| └ | name | External ❗️ |   |NO❗️ |
| └ | symbol | External ❗️ |   |NO❗️ |
| └ | decimals | External ❗️ |   |NO❗️ |
||||||
| **Context** | Implementation |  |||
| └ | _msgSender | Internal 🔒 |   | |
| └ | _msgData | Internal 🔒 |   | |
||||||
| **SafeMath** | Library |  |||
| └ | add | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | mul | Internal 🔒 |   | |
| └ | div | Internal 🔒 |   | |
| └ | div | Internal 🔒 |   | |
| └ | mod | Internal 🔒 |   | |
| └ | mod | Internal 🔒 |   | |
||||||
| **Address** | Library |  |||
| └ | isContract | Internal 🔒 |   | |
| └ | sendValue | Internal 🔒 | 🛑  | |
| └ | functionCall | Internal 🔒 | 🛑  | |
| └ | functionCall | Internal 🔒 | 🛑  | |
| └ | functionCallWithValue | Internal 🔒 | 🛑  | |
| └ | functionCallWithValue | Internal 🔒 | 🛑  | |
| └ | functionStaticCall | Internal 🔒 |   | |
| └ | functionStaticCall | Internal 🔒 |   | |
| └ | functionDelegateCall | Internal 🔒 | 🛑  | |
| └ | functionDelegateCall | Internal 🔒 | 🛑  | |
| └ | _verifyCallResult | Private 🔐 |   | |
||||||
| **Ownable** | Implementation | Context |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | owner | Public ❗️ |   |NO❗️ |
| └ | renounceOwnership | Public ❗️ | 🛑  | onlyOwner |
| └ | transferOwnership | Public ❗️ | 🛑  | onlyOwner |
| └ | getUnlockTime | Public ❗️ |   |NO❗️ |
||||||
| **Manageable** | Implementation | Context |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | manager | Public ❗️ |   |NO❗️ |
| └ | transferManagement | External ❗️ | 🛑  | onlyManager |
||||||
| **IPancakeV2Factory** | Interface |  |||
| └ | createPair | External ❗️ | 🛑  |NO❗️ |
||||||
| **IPancakeV2Router** | Interface |  |||
| └ | factory | External ❗️ |   |NO❗️ |
| └ | WETH | External ❗️ |   |NO❗️ |
| └ | addLiquidityETH | External ❗️ |  💵 |NO❗️ |
| └ | swapExactTokensForETHSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
||||||
| **Tokenomics** | Implementation |  |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | _addFee | Private 🔐 | 🛑  | |
| └ | _addFees | Private 🔐 | 🛑  | |
| └ | _getFeesCount | Internal 🔒 |   | |
| └ | _getFeeStruct | Private 🔐 |   | |
| └ | _getFee | Internal 🔒 |   | |
| └ | _addFeeCollectedAmount | Internal 🔒 | 🛑  | |
| └ | getCollectedFeeTotal | Internal 🔒 |   | |
||||||
| **Presaleable** | Implementation | Manageable |||
||||||
| **BaseRfiToken** | Implementation | IERC20, IERC20Metadata, Ownable, Presaleable, Tokenomics |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | name | External ❗️ |   |NO❗️ |
| └ | symbol | External ❗️ |   |NO❗️ |
| └ | decimals | External ❗️ |   |NO❗️ |
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | Public ❗️ |   |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
| └ | burn | External ❗️ | 🛑  |NO❗️ |
| └ | _burnTokens | Internal 🔒 | 🛑  | |
| └ | increaseAllowance | Public ❗️ | 🛑  |NO❗️ |
| └ | decreaseAllowance | Public ❗️ | 🛑  |NO❗️ |
| └ | isExcludedFromReward | External ❗️ |   |NO❗️ |
| └ | reflectionFromToken | External ❗️ |   |NO❗️ |
| └ | tokenFromReflection | Internal 🔒 |   | |
| └ | excludeFromReward | External ❗️ | 🛑  | onlyOwner |
| └ | _exclude | Internal 🔒 | 🛑  | |
| └ | includeInReward | External ❗️ | 🛑  | onlyOwner |
| └ | setExcludedFromFee | External ❗️ | 🛑  | onlyOwner |
| └ | isExcludedFromFee | Public ❗️ |   |NO❗️ |
| └ | _approve | Internal 🔒 | 🛑  | |
| └ | _isUnlimitedSender | Internal 🔒 |   | |
| └ | _isUnlimitedRecipient | Internal 🔒 |   | |
| └ | _transfer | Private 🔐 | 🛑  | |
| └ | _transferTokens | Private 🔐 | 🛑  | |
| └ | _takeFees | Private 🔐 | 🛑  | |
| └ | _getValues | Internal 🔒 |   | |
| └ | _getCurrentRate | Internal 🔒 |   | |
| └ | _getCurrentSupply | Internal 🔒 |   | |
| └ | _beforeTokenTransfer | Internal 🔒 | 🛑  | |
| └ | _getSumOfFees | Internal 🔒 |   | |
| └ | _isV2Pair | Internal 🔒 |   | |
| └ | _redistribute | Internal 🔒 | 🛑  | |
| └ | _takeTransactionFees | Internal 🔒 | 🛑  | |
||||||
| **Liquifier** | Implementation | Ownable, Manageable |||
| └ | <Receive Ether> | External ❗️ |  💵 |NO❗️ |
| └ | initializeLiquiditySwapper | Internal 🔒 | 🛑  | |
| └ | liquify | Internal 🔒 | 🛑  | |
| └ | _setRouterAddress | Private 🔐 | 🛑  | |
| └ | _swapAndLiquify | Private 🔐 | 🛑  | lockTheSwap |
| └ | _swapTokensForEth | Private 🔐 | 🛑  | |
| └ | _addLiquidity | Private 🔐 | 🛑  | |
| └ | setRouterAddress | External ❗️ | 🛑  | onlyManager |
| └ | setSwapAndLiquifyEnabled | External ❗️ | 🛑  | onlyManager |
| └ | _approveDelegate | Internal 🔒 | 🛑  | |
||||||
| **Antiwhale** | Implementation | Tokenomics |||
| └ | _getAntiwhaleFees | Internal 🔒 |   | |
||||||
| **SafeToken** | Implementation | BaseRfiToken, Liquifier, Antiwhale |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | _isV2Pair | Internal 🔒 |   | |
| └ | _getSumOfFees | Internal 🔒 |   | |
| └ | _beforeTokenTransfer | Internal 🔒 | 🛑  | |
| └ | _takeTransactionFees | Internal 🔒 | 🛑  | |
| └ | _burn | Private 🔐 | 🛑  | |
| └ | _takeFee | Private 🔐 | 🛑  | |
| └ | _takeFeeToETH | Private 🔐 | 🛑  | |
| └ | _approveDelegate | Internal 🔒 | 🛑  | |
||||||
| **BABYSPACEFLOKI** | Implementation | SafeToken |||
| └ | <Constructor> | Public ❗️ | 🛑  | SafeToken |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
