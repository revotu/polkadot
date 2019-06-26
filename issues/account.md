## account issues

### 1.三种类型的account：STASH/CONTROLLER/SESSION？

SESSION必须用`ED25519`的曲线，其他的`SR25519`和`ED25519`都可以。

STASH可以理解成冷钱包，存了大量的资产。

CONTROLER是用来控制STASH已经bonded金额的投票给谁，开始投票，结束投票的控制作用。（存少量的钱，用来交易手续费的消耗）。

SESSION不存钱，只是validator节点用来签名区块用的。

https://wiki.polkadot.network/en/latest/polkadot/learn/keys/
