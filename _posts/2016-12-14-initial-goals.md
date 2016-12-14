---
published: true
---

# Outline
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
    
# Reading
I found a writeup by [Rogelio Nicolas Mengual](https://www.toptal.com/data-science/algorithmic-trading-a-practical-tale-for-engineers) which details his expereince getting his hands wet with automated Forex trading.  I have read the post, but I need to read the links he referenced more thoroughly.

## Links
- [babypips](http://www.babypips.com/school)
- [The Way of the Turtle](https://www.amazon.com/Way-Turtle-Methods-Ordinary-Legendary/dp/007148664X)
- [Technical Analysis Trading Professional Edition](https://www.amazon.com/Technical-Analysis-Trading-Professional-Edition/dp/007175914X)
- [Expert Advisor Programming Automated MetaTrader](https://www.amazon.com/Expert-Advisor-Programming-Automated-MetaTrader/dp/0982645902)
- [Trading Systems Development Portfolio Optimisation](https://www.amazon.com/Trading-Systems-Development-Portfolio-Optimisation/dp/1905641796)
- [A Step-By-Step Implementation of a Multi-Agent Currency Trading System](http://www.igi-global.com/chapter/step-step-implementation-multi-agent/49365)

## Plan
Attempt to obtain and read all of the given material.  Make a blog post about each and how the source relates to the end goal.  To create a custom trading suite.
    
<iframe src="https://webrates.truefx.com/rates/webWidget/trfxhp.jsp?l=n&amp;t=250" width="100%" height="370" scrolling="no" frameborder="0" padding="0" margin="0"> </iframe>
