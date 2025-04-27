---
icon: arrow-trend-up
---

# APilot

## <mark style="color:green;">I. What is APilot?</mark>

APilot is a high-performance quantitative trading framework focused on cryptocurrency and stock markets, developed by the AlphaPilot.tech team. The framework supports both strategy backtesting and live trading, providing a comprehensive solution for quantitative traders.

**Opensource Link**: [https://github.com/AlphaPilotHQ/apilot](https://github.com/AlphaPilotHQ/apilot)

***

### <mark style="color:green;">II. Key Features</mark>

* **Event-driven architecture**: Built for high-performance, real-time trading systems
* **Multiple trading strategies**: Price Action strategies, Factor strategies (in development)
* **Professional execution algorithms**: BestLimit, TWAP algorithms
* **Comprehensive backtesting**: Accurate simulation with detailed performance analytics
* **Multi-exchange support**: Currently focusing on Binance, with more to come
* **Live trading capability**: Execute strategies in real-time with risk management
* **Extensible framework**: Easy to add new strategies, data sources, and exchanges

***

### <mark style="color:green;">III. Strategy Types</mark>

* **Price Action (PA) strategies**: Support for trend following, mean reversion, and other classic price action strategies
* **Factor strategies**: Quantitative strategies based on multi-factor models (in development)

***

### <mark style="color:green;">IV. Technical Architecture</mark>

* **Core Module**: Contains all abstract interfaces and core data structures
  * Abstract base classes (BaseEngine, BaseGateway, etc.)
  * Data models (OrderData)
  * Constant definitions (Direction, Interval, etc.)
  * Basic event system
* **Feature Modules**: Specific implementations for different domains
  * `execution/gateway/` - Exchange API implementations
  * `engine/` - Specific engine implementations
  * `strategy/` - Trading strategy templates and implementations
  * `performance/` - Performance calculation and reporting
