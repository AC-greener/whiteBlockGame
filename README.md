# whiteBlockGame
Js实现别踩白块小游戏


##游戏思路
1.  先创建一个正方形，将其分成16块
2. 将最上面一行上移并隐藏(黑块要不断地从上面掉落下来)
3. 这些黑块肯定要让Js动态生成啊，可以一行一行的生成，
而每一行都是由四个cell组成，（黑色的那块多加一个class="black"就行啦）， 选哪一块作为黑色呢？ 就要用到随机数了
4.让方块动起来
主要是Js操作dom， 添加定时函数setInterval（）使方块匀速下落，在移动的同时，要判断最下面一行黑色的方块是否触底，
触底则游戏失败，如何判断鼠标点到黑色方块呢？ 只需要添加一个judge函数就ok了

##游戏效果图：
![未正常显示](https://github.com/AC-greener/whiteBlockGame/raw/master/img/game1.png)
![未正常显示](https://github.com/AC-greener/whiteBlockGame/raw/master/img/game2.png)
