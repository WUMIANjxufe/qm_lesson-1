# 抛物线&数学

- 数学公式
    支持抛物线运动
    x 没有加速度 1000 = speed * time
    y 重力的作用 加速度 A = 2 *(YEnd - YStart) / (Time* Time)
    起始点 0 0
    终止点 1000 1000

- 实现方案
    1. 定位
    2. 怎么让它一直动？ setInterval定时器
    requestAnimationFrame(fn)