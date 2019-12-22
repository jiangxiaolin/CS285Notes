# CS285Notes
CS285学习笔记

课程地址：https://www.bilibili.com/video/av66523922

课件地址：http://rail.eecs.berkeley.edu/deeprlcourse/


第二讲：Supervised Learning of Behaviors  行为的有监督学习

讲的是使用模仿学习（序列决策的监督学习）进行学习，能不能起到作用？

能 但是需要大量的数据

那如何收集数据：  
1、使用已有数据训练策略  
2、运行策略得到新的数据  
3、人工标注这部分新的数据  
4、合并所有的数据

如果使用这样的方式收集数据，还是需要人工参与标注。是否能不需要更多的数据的情况下，  
也让模型work呢？

有两个困难：
a、不是马尔科夫决策问题 b、多模态行为

以自动驾驶为例：
使用cnn进行状态表示，使用rnn进行连续action建模

然后对模仿学习进行了总结概述：
Often (but not always) insufficient by itself  
     • Distribution mismatch problem  
Sometimes works well    
     • Hacks (e.g. left/right images)  
     • Samples from a stable trajectory distribution   
     • Add more on-policy data, e.g. using Dagger   
     • Better models that fit more accurately  
     
    
    
模仿学习的问题在哪？  
1、人类需要提供数据，这个数据肯定是有限的：深度学习往往在数据充足的时候起作用  
2、人类不善于提供各种action  
3、人类可以自动学习，不断自我提升，机器人可以做到吗  


总的来说，介绍了一下模仿学习。可以和后面的强化学习对比






     
