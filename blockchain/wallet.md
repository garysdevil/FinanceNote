## 去中心化数字货币钱包
1. 创建钱包时设置强度足够的交易密码，它用来加密钱包文件 Keystore。

2. 保存 Keystore 钱包文件到电子邮箱或离线优盘。前提是交易密码足够强，这样即便你的邮箱被攻破了，黑客拿到你的 Keystore 也无法暴力破解。

3. 保存 助记词 到物理介质上，比如抄在卡纸上。当你忘记交易密码时，助记词可以恢复钱包、重置密码。

## 钱包
### Salana
- https://zhuanlan.zhihu.com/p/365417390

### Polkadot
- https://github.com/polkadot-js/extension
- https://github.com/polkadot-js/apps/
- https://polkadot.js.org/docs/
- https://www.chainnews.com/articles/616066440423.htm

```bash
# 自建区块链游览器
docker run  --name polkadot-ui -p 8080:80 -d  jacogr/polkadot-js-apps
```

### metamask钱包
- 钱包 https://github.com/MetaMask/metamask-extension