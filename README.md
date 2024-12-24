**这个数据包为您提供了站在铁块上向上传送的功能**

如果遇到任何问题，请点击 [这里](https://github.com/WhiteElephant-abc/anvil-falling/issues/new) 反馈

如果无法访问，可点击 [这里](https://steampp.net/) 下载加速器

## 主要功能

### 铁块电梯

- 玩家站在上下两个铁块之间时向上传送
- 最远传送距离为 6 格，即两个铁块的最大间距为 5 格
- 不会传送旁观者，会传送生物及非生物实体

### 信标起飞

- 需要通过`scoreboard  players  set  BeaconFly  BeaconFly  1`开启
- 可以通过`scoreboard  players  set  BeaconFly  BeaconFly  0`关闭
- 信标下有铁块、金块、绿宝石块、钻石块或时会将玩家向上传送（不传送旁观者）
- 如果游戏版本为 1.21 及以上，还可以识别下界合金块
- 高度依次为 20、40、60、80、100 格；
- 相同的方块可以叠加高度（最高为 400 格，使用四个下界合金块），如果方块不同，将以距离信标最近的方块为准。