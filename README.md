# Plane-War（飞机大战）                               
1.游戏运行环境：windows                               
2.游戏制作语言：python2.7.6；使用主要库：pygame；打包工具：py2exe                            
3.游戏内容：             
  我方飞机移动：wasd或键盘方向键                               
  使用全屏炸弹：键盘空格键      
  其他：游戏左上方显示玩家分数，右上方是暂定按钮；左下方是全屏炸弹个数；右下方是我方飞机生命数                
  内容介绍：         
  1）游戏一开始，我方飞机有3条命，3个全屏炸弹     
  2）敌方飞机有3种：小型机（1000分/只，1滴血），中型机（6000分/只，8滴血），大型机（10000分/只，20滴血）     
  3）游戏开始后每30秒就发放一次道具补给，分别是：超级子弹（持续18秒），全屏炸弹（最多携带3个）
  4）游戏难度：（玩家达到一定分数时自动增加难度等级）
      level 1（<50000分）：小型机15只，中型机4只，大型机2只
      level 2（>50000）：增加3架小型机，2架中型机，1架大型机；提升小型机的速度
      level 3（>200000）：增加5架小型机，3架中型机，2架大型机；提升小型机和中型机的速度
      level 4（>450000）：增加5架小型机，3架中型机，2架大型机；提升小型机和中型机的速度
      level 5（>800000）：增加5架小型机，3架中型机，2架大型机；提升小型机和中型机的速度
