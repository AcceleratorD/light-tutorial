# Dex画线机器人

## 使用场景：

用于在给定的价格范围中, 做随机波动, 并制造一些成交量,提高盘口活跃度并绘制dex品种交易k线。

## 参数说明：

价格范围: 数字由低到高填写, 用来控制画线范围, 超出范围时, 机器人会尽力往设定范围内运行\
\
每次成交量: 数字由低到高填写,每次交易的交易量随机范围,范围可以设置大一些保证交易记录看起来更自然\
\
间隔时间: 每次运行的时间间隔, 由于dex交易手续费和gas费用成本较高, 建议最低填写30秒\
\
趋势方向: 画线机器人工作时候默认会参考大行情的方向, 本参数可以进一步调整震荡方向

## 启动和停止：

点击启动按钮，机器人会立即开始工作。遇到各种原因导致的下单失败或买卖盘口差价极小时，机器人将暂停工作
