-------------------------------------------------------------------
○TouHou Project　～ 弹幕开花宣言（Fighters）

　游戏设定与后记等等

　开发心得地址：=[[http://blog.kyrios.cn/2017/05/15/sfml_th20/](https://blog.kyrios.cn/2017-ccpp-coursework/)][1]
　　　　　　　　　　　　　　　　　
　　　　　　　　　　　　　　　　　　　　　　　        2017/06/14
-------------------------------------------------------------------

====================================================================


■附言
====================================================================

　大家好，我是Kyr1os。
　初期的工作基本结束了，后面有时间的话（flag）大概会重构代码和附加关卡的开发。
　首先感谢东方系列的原作者：上海爱丽丝幻乐团长　ＺＵＮ
　所有的素材都是基于上海爱丽丝幻乐团的作品做了些改动搬过来的
　标题也是借用的花映冢的副标题来着，总之十分感谢！
　最开始也只是当做一份普通的C++课程作业来完成的
 　但由于作者本人很喜欢钻弹幕的原因，没有有趣的弹幕来挑战总是觉得有些无聊
  　然后
  > 每天都在漫长地挑战不知道能不能躲过去的开发途中的弹幕。
如果知道能不能躲过去还好，但是在开发阶段通过是不是可能只有自己去尝试了。
真正的地狱其实在开发现场！
（……下次作一个更和善点的游戏吧）
  　
   
　和ZUN开发绀珠传的感想差不多啊...

>　因为已经完成了，所以噩梦已经离开了我的手中。
　这次噩梦应该会来到你身边吧。

　毕竟从代码上看好像只写了两残来着
 　打不过的话自己改改残机数吧，只要多加练习两残应该也能打完一面的。
　
　对于初心者来说可能是Lunatic难度，但是只要记住了出现怪物的位置就能减少一半以上的弹幕！
 　从华丽的弹幕中潇洒的穿过去并击破的感觉应该很棒吧，希望你也能享受这种感觉。
  
  　最后简单的谈一下代码...结构上讲层次设计的感觉还是有问题。重构的时候大概会把层次感体现出来。不过由于每个模块设计的很小的原因，测试起来倒是异常的方便。由于偷懒把很多参数都写成了public（感觉就快变成普通的结构体了2333）。最好是能写一些接口函数给封装起来。对于属性的设置也整合一下会好很多。3K行代码看起来很多，但是感觉重构一下的话至少可以减少20%左右的代码量。
   
   　又自说自话的写了一大堆东西，还是早点去睡觉好了，再不~~预习~~复习怕是要出事情2333.  



　　　　　　　　　　　　　　　　Kyr1os


  [1]: http://blog.kyrios.cn/2017/05/15/sfml_th20/
