# MerkleTree 生成白名单

`MerkleTree` 现在普遍用来做线上数据验证。这个项目实现使用 MerkleTree 做 NFT 白名单验证。

## Merkle 树

详情请参见：https://en.wikipedia.org/wiki/Merkle_tree



[![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Hash_Tree.svg/1920px-Hash_Tree.svg.png)](MerkleTree)

## 项目运行

```git clone https://github.com/CourteousBin/Merkletreewhitelist.git```

```cd ./Merkletreewhitelist```

```npm install```

```node ./index.js```

[remix 部署合约：MerkleTreeWhileList.sol 验证结果](https://remix.ethereum.org/)

**注意：部署合约需要传入 root 初始化，也就是 index.js 第24行**