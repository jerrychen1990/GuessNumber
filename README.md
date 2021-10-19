# GuessNumber
猜数字游戏AI:[游戏规则](https://zh.wikipedia.org/wiki/%E7%8C%9C%E6%95%B0%E5%AD%97)

采用蒙特卡洛搜索树探索最优的猜测，每次猜数尽量剪枝。
经过100次测试，平均使用4.52步才出结果。

运行
```python
./guess_number.py --game_num=5 
```
和AI进行5局比拼，哪方用的总步数少获胜，反正我是赢不了我的AI😂

