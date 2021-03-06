# ReadSetTrade Indicators
## RST Custom EMA and VWAP
TBD

## RST Custom RSI
TBD

# ReadSetCrypto Indicators

## RSC Trend Trading Indicator
This RSC Trend Trading Indicator provides Buy and Sell signals using Donchian channels and simple moving averages.

### Buy:
- Price hits upper Donchian channel (period 20)
- Closing price is above 50 SMA
- Closing price is above 200 SMA
### Sell:
Price hits lower Donchian channel (period 10)

## BTC Onchain Indicator
This BTC Onchain Indicator uses onchain data to provide different Pricing Models for trend determination.

### Features

- Linear Regression of Difficulty
- Difficulty Ribbon
- Stock to Flow Price
- Average and Top Price
- 128 and 200 DMA
- 128 and 200 WMA
- Mayer Multiple Pricing Bands

## BTC Multiples Indicator
This BTC Indicator provides several multiples for top and bottom detection.

### Features

- Mayer Multiple
- Stock to Flow Multiple
- Linear Regression of Difficulty Multiple
- Puell Multiple https://www.lookintobitcoin.com/charts/puell-multiple/

## BTC Golden Ratio Indicator
This BTC Indicator is based on the article from Philipp Swift:  
https://medium.com/@positivecrypto/the-golden-ratio-multiplier-c2567401e12a

It is supposed to give you bottom and top signals. Historically those signals have worked pretty well.

# Add Script to Tradingview Chart

1. Go into Pine Editor and click **New**
2. Paste [code](scripts)
 into editor area

![AddScriptToTV_Step1.png](images/AddScriptToTV_Step1.png)

3. Click **Untitled Script** and enter name
4. Click **Save**
5. Click **Add to Chart**

![AddScriptToTV_Step2.png](images/AddScriptToTV_Step2.png)
