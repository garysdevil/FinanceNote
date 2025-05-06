---
created_date: 2022-10-20
---

[TOC]

## 量化
- 量化投资
    - 应用数学技术对投资过程进行精确和优化的改良。

- 量化交易
    - 是指以先进的数学模型替代人为的主观判断，利用计算机技术从庞大的历史数据中海选能带来超额收益的多种“大概率”事件以制定策略，极大地减少了投资者情绪波动的影响，避免在市场极度狂热或悲观的情况下作出非理性的投资决策。


## 交易所
### Binance
1. Binance API 
    - https://www.binance.com/zh-CN/support/announcement/115000840592
    - https://binance-docs.github.io/apidocs/spot/cn/#185368440e

2. Python SDK 
    - https://github.com/binance/binance-connector-python

### OKX
1. OKX API
    - https://www.okx.com/docs-v5/zh/#overview

2. Python SDK 
    - https://github.com/okex/V3-Open-API-SDK
    - https://github.com/coinrising/okex-api-v5
    - https://github.com/jane-cloud/Open-API-SDK-V5

3. 子账户
    - 支持币币交易，合约交易，ETT交易，不支持法币交易，充值，提现

4. 托管子账户
    - 一般用于将资金托管给交易团队。 



```python
result = swapAPI.take_order(instrument_id='', type='', price='', size='',order_type='', match_price='')
# client_oid: 设置的订单ID
# type: 1:开多2:开空3:平多4:平空
# price：每张合约的价格
# size: 买入或卖出合约的数量（以张计数）
# match_price:是否以对手价下单(0:不是 1:是)
# leverage：杠杆倍数，1-100的整数
```

## 数字量化交易SDK ccxt
- https://github.com/ccxt/ccxt
- https://my.oschina.net/u/4352984/blog/4839943
- ccxt库目前支持以下131个加密货币交易所和交易API

## 量化交易SDK
- https://github.com/freqtrade/freqtrade
- https://github.com/vnpy/vnpy
- https://github.com/scrtlabs/catalyst
- https://github.com/StockSharp/StockSharp
- https://github.com/jesse-ai/jesse
- https://github.com/iterativv/NostalgiaForInfinity
- 量化相关python包整理 https://zhuanlan.zhihu.com/p/441990336

## 术语
### 三大经典量化指标
- 夏普比率(Shape Ratio)，也称夏普指数
    - 投资回报与风险的比例

- 詹森指数(Jensen)，也称为阿尔法值
    - 衡量基金超额收益大小的一种指标

- 特雷诺指数(Treynor Ratio，TR)
    - 每单位风险获得的风险溢价。特雷诺指数越大，单位风险溢价越高，绩效越好；相反，特雷诺指数越小，单位风险溢价越低，绩效越差。

### 常用量化名词
- 策略收益(total returns)，策略实际收益额。

- 基准收益(Benchmark Returns)，策略最低收益额。

- HFT 高频交易(High frequentcy trade)

- 低频交易

- β/beta/贝塔收益
    是指跟随大盘上涨获得的收益。

- α/alpha/阿尔法收益
    - 是指投资跑赢大盘的收益。