##Pinescript v4 Example Projects

These are a small sample of projects I worked on in pinescript from 2019-2021. They all use Pinscript version 4 and have not been rewritten for version 5. However, when briefly tested they still compile and appear to function correctly. 

*NOTE: These files are for example only and are written in an older version of PineScript (v4). As of their initial uploading to this repository they do not incorporate many of the great changes that have been made in the few years since being written. They should be used as reference only. If you intend to use any of the code from these files, further research is recommended.*

###Levels
FILE: *levels.pine*

This displays a panel showing various support and resistance levels based on ATR, recent fractal high/lows (peaks), pre-market high/low, prev day close, and various EMAs.

I primarily used this information when I was doing overnight gapper trades and looking for big bull retracement moves.

###Stoch RSI Tests
FILE: *stoch-rsi-tests.pine*

This strategy watched for Stochastic RSI extremes (below 10 and above 90), and bought/sold respectively. I was developing this for an established bitcoin scalper who already traded this strategy manually and wanted a quant to assist with his trading.

###Trendline Break Strategy
FILE: *trendline-break-strategy.pine*

This strategy established a trend based on repeating higher high / higher low fractals (peaks) then watched for a reversal of trend based on support/resistance also determined by fractals.

It incorporated a trailing stop, EMA cross profit target exits, timeframe based trading, and price action candle patterns for it's trade management strategy.
