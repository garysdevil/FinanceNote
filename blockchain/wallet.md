## 去中心化数字货币钱包
1. 创建钱包时设置强度足够的交易密码，它用来加密钱包文件 Keystore。

2. 保存 Keystore 钱包文件到电子邮箱或离线优盘。前提是交易密码足够强，这样即便你的邮箱被攻破了，黑客拿到你的 Keystore 也无法暴力破解。

3. 保存 助记词 到物理介质上，比如抄在卡纸上。当你忘记交易密码时，助记词可以恢复钱包、重置密码。

## 钱包
### Salana公链钱包
- https://zhuanlan.zhihu.com/p/365417390

### Polkadot公链钱包
- https://github.com/polkadot-js/extension
- https://github.com/polkadot-js/apps/
- https://polkadot.js.org/docs/
- https://www.chainnews.com/articles/616066440423.htm

```bash
# 自建区块链游览器
docker run  --name polkadot-ui -p 8080:80 -d  jacogr/polkadot-js-apps
```

### metamask钱包/以太坊生态
- 钱包 https://github.com/MetaMask/metamask-extension
- 支持以太坊生态的代币

### Keplr钱包/Cosmos生态
- 支持Cosmos生态的代币

### imToken钱包
- 支持各种公链的代币


## 开源的通信协议 WalletConnect
- WalletConnect在DApp和手机钱包之间建立了通信，所以WalletConnect是一个开源的通信协议。
- 在DApp上用WalletConnect，需要手机上安装一个集成了WalletConnect的钱包，然后在浏览器上访问DApp时，通过WalletConnect建立手机钱包和DApp的通信。之后DApp的连接钱包、授权、签名交易等等，都会发送到手机端，用户在手机钱包上完成确认。