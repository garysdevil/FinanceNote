## 去中心化数字货币钱包
1. 创建钱包时设置强度足够的交易密码，它用来加密钱包文件 Keystore。

2. 保存 Keystore 钱包文件到电子邮箱或离线优盘。前提是交易密码足够强，这样即便你的邮箱被攻破了，黑客拿到你的 Keystore 也无法暴力破解。

3. 保存 助记词 到物理介质上，比如抄在卡纸上。当你忘记交易密码时，助记词可以恢复钱包、重置密码。

## 开源的通信协议 WalletConnect
- WalletConnect在DApp和手机钱包之间建立了通信，所以WalletConnect是一个开源的通信协议。
- 在DApp上用WalletConnect，需要手机上安装一个集成了WalletConnect的钱包，然后在浏览器上访问DApp时，通过WalletConnect建立手机钱包和DApp的通信。之后DApp的连接钱包、授权、签名交易等等，都会发送到手机端，用户在手机钱包上完成确认。

## 特殊钱包
### Polkadot生态/DOT/Polkadot钱包
- https://github.com/polkadot-js/extension
- https://github.com/polkadot-js/apps/
- https://polkadot.js.org/docs/
- https://www.chainnews.com/articles/616066440423.htm

```bash
# 自建区块链游览器
docker run  --name polkadot-ui -p 8080:80 -d  jacogr/polkadot-js-apps
```

### Solana生态/SOL/Phantom钱包
- 官网 https://phantom.app/
- 支持Google插件 https://chrome.google.com/webstore/detail/phantom/bfnaelmomeimhlpmgjnjophhpkkoljpa
- 支持各种操作系统和各种游览器的插件。
- Solana生态相关的钱包 https://zhuanlan.zhihu.com/p/365417390

### 以太坊生态/ETH/Metamask钱包 小狐狸
- 官网 https://metamask.io/
- 开源 是 https://github.com/MetaMask
- 支持Google插件 https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn

### Cosmos生态/ATOM/Keplr钱包
- 官网 https://www.keplr.app/
- 开源 是 https://github.com/chainapsis
- 支持Google插件 https://chrome.google.com/webstore/detail/keplr/dmkamcknogkgcdfhhbddcghachkejeap

### Tron生态/TRX/TronLink钱包 波宝
- 官网 https://www.tronlink.org/
- Google插件 https://chrome.google.com/webstore/detail/tronlink/ibnejdfjmmkpcnlpebklmnkoeoihofec
- 公链代币 TRX
- 简介 Tron生态最早的插件钱包

### Dfinity生态/ICP/Plug钱包
- 官网 https://plugwallet.ooo/
- 支持Google插件 https://chrome.google.com/webstore/detail/plug/cfbfdhimifdmdehjmkdobpcjfefblkjm

### Filecoin生态/FIL/FoxWallet钱包
- 官网 https://foxwallet.com/
- 开源 否
- 不支持Google插件

### Filecoin生态/FIL/FilFox网页版钱包
- 钱包 https://wallet.filfox.info/
- 开源 否

## Arweave生态/AR/Google插件钱包
- 官网 https://www.arconnect.io/
- Google插件地址 https://chrome.google.com/webstore/detail/arconnect/einnioafmpimabjcddiinlhmijaionap/related
- 开源 https://github.com/th8ta/arconnect

## Arweave生态/AR/网页钱包
- 官网 https://arweave.app/
- 开源 https://github.com/jfbeats/ArweaveWebWallet

## 公链钱包
### imToken钱包
- 官网 https://token.im/
- 开源 是 https://github.com/consenlabs 界面UI代码不开源
- 支持各种公链的代币
- 不支持Google插件

### TrustWallet钱包
- 官网 https://trustwallet.com/
- 开源 是 https://github.com/trustwallet
- Biance 2018年收购的去中心化数字货币钱包
- 不支持Google插件

### BitKeep钱包
- 官网 https://bitkeep.com/
- 开源 否
- Google插件 https://chrome.google.com/webstore/detail/bitkeep-bitcoin-crypto-wa/jiidiaalihmmhddjgbnbgdfflelocpak/related

