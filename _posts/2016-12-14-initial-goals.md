---
published: true
---
- Evaluate TrueFX as a platform to make automated trading decisions by implementing the pieces needed to conduct backtesting on a single algorithm
- [API Integration](https://github.com/imkarrer/truefx)
- DAL and persistent storage
    - Need to implement a data access layer around the persistent storage tech selected (most likely mysql)
    - Private API client for interacting with DAL via REST
- Historical Data ingest
- Basic algorithm implementation
    - Some super simple algo that uses basic tools as indicators.  Picking this algorithm will drive what tools I need to implement.
- Basic tool implementation
    - Candle sticks
    - Moving average
- Widget
    - Use the TrueFX widget to track the currency pairs for which I plan to backtest.  The widget with default settings is displayed below.
    
<iframe src="https://webrates.truefx.com/rates/webWidget/trfxhp.jsp?l=n&amp;t=250" width="100%" height="370" scrolling="no" frameborder="0" padding="0" margin="0"> </iframe>
