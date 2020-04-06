# 已知问题 Known issue

- **无法处理夜间委托的弹窗** 晚上22点会弹出夜间委托(国服21点), 如果在战斗中, 则在战斗后显示, 否则立即弹出.
- **演习可能SL失败** 演习看的是屏幕上方的血槽, 血槽可能被立绘遮挡, 因此需要一定时间(默认1s)血量低于一定值(默认40%)才会触发SL.  一个血皮后排就有30%左右的血槽, 所以别以为在1s内被打掉40%是不可能的. 另外如果后排立绘过大且CD重叠严重, 建议增大确认时间(比如3s), 这样可以减少误判.
- **会显示绿脸黄脸红脸, 红脸出击确认** 这个是瓜游心情值更新不及时的锅了, 只要填对了`RECOVER_PER_HOUR` 和 `EMOTION_LIMIT` 就绝对不会红脸出击, 当然, 也可以保证一直处于经验加成状态. 请相信`module.combat.emotion` 
- **有时无法识别舰队图标**
- **不支持潜艇** 潜艇会干扰普通舰队的识别.
- **无法处理网络波动** 重连弹窗, 跳小黄鸡
- **拖动操作在极少数情况下无效**



# TODO

- **适配更多地图**
- **支持潜艇** 道中出击, BOSS站出击, BOSS出现后召唤潜艇
- ~~跳过指挥喵削血动画~~ 已完成
- **阵型选择** 单纵阵 复纵阵 轮形阵
- **先锋血量平衡** 把血少的拖到保护位, 这对 低耗队, 练级队很有用.
- **练级队优化** 拣弹药, 主动踩伏击, 低血量撤退
- **处理夜间委托的弹窗**
- **出击自动站桩** 打低级图的时候, 自律瞎动会超出射程, 站在中间不动打得更快
- **自动收菜** 委托, 紧急委托, 科研, 后宅喂食, 学技能, 大讲堂, 收小卖部
- **新地图敌人统计** 不用再等wiki更新了