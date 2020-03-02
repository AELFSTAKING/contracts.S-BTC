# contracts.S-BTC



## 介绍

基于etherum智能合约，由solidity语言编写，s-btc代币是btc主链币的等比例兑换，它也是扩展了功能的erc20代币合约。https://eips.ethereum.org/EIPS/eip-20



## 主要功能

#### 1.orderCreate

挂单方法，需传入_to（此处应该传staking合约的地址），_value（挂单金额），_message（挂单附加信息）。

#### 2.transferWithMsg

转账方法，需传入_to（目的地址），_value（转账金额），_message（转账附加信息）。

#### 3.transferToMultiAddresses

批量转账方法，需传入_addresses（目的地址集合），_amounts（转账金额集合），_message（转账附加信息）。



## 部署方式

使用etherum的solidity官方IDE：http://remix.ethereum.org/
