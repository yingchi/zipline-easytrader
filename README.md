## Intro
This is a personal project that trying to combine [zipline](https://github.com/quantopian/zipline) with [easytrader](https://github.com/shidenggui/easytrader). 然后对接雪球组合实现自动化交易的模拟实盘。

## Todo
1. If captcha is needed for Xueqiu login, refer to https://github.com/kanghua309/easytrader/commit/46c40052a3fb2373ea6e97d254f85a6b2fd47c94 and try to modify the code in easytrader.


### easytrader

* 进行自动的程序化股票交易
* 支持跟踪 `joinquant`, `ricequant` 的模拟交易
* 支持跟踪 雪球组合 调仓
* 支持通用的同花顺客户端模拟操作
* 实现自动登录
* 支持通过 webserver 远程操作客户端
* 支持命令行调用，方便其他语言适配
* 支持 Python3, Linux / Win, 推荐使用 `Python3`

#### 实盘易

如果有对其他券商或者通达信版本的需求，可以查看 [实盘易](http://www.iguuu.com/e?x=19828)

#### 模拟交易

* 雪球组合 by @[haogefeifei](https://github.com/haogefeifei)（[说明](doc/xueqiu.md)）

#### 使用文档

[中文文档](http://easytrader.readthedocs.io/zh/master/)
[软件实现原理](http://www.jisilu.cn/question/42707)
