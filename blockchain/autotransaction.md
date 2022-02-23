## Binance
1. Binance API 
    - https://www.binance.com/zh-CN/support/announcement/115000840592
    - https://binance-docs.github.io/apidocs/spot/cn/#185368440e

2. Python SDK 
    - https://github.com/binance/binance-connector-python

## OKX
1. OKX API
    - https://www.okx.com/docs-v5/zh/#overview

2. Python SDK 
    - https://github.com/okex/V3-Open-API-SDK
    - https://github.com/coinrising/okex-api-v5

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
