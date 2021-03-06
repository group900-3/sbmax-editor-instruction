# 自动保存策略

首先我们要明确，关卡数据分为两种。  
我们在本地新建的、用于测试的数据，被认为是草稿数据。这些数据仅保存在本地。  
当草稿通过测试，发布到网络时，这个数据会被复制变为正式的共享关卡数据。  
一旦关卡数据被发布，它就与本地的草稿不再有关联，你不能修改已经发布到网络的关卡。

所以，你在编辑器中操作的将永远都是一份草稿数据。  
我们想过几种保存数据的方案，包括手动保存与自动保存  
但鉴于我们操作的只是一款游戏中的关卡草稿数据，我们还是认为一个简单的自动保存方案更加适合  

当你使用编辑器修改任意物体或砖块的属性，编辑器就会自动保存数据  
你可以在任何时候关闭游戏，下次打开关卡将保持你上次编辑的状态  

但是这带来一个问题：当你对关卡进行了一些修改后，你可能并不满意修改后的结果，但这时想恢复草稿最初的状态就很难了  
这种情况下，我们在草稿列表中提供了草稿的复制功能，如果你觉得当前的草稿已经比较完美，你应该复制一份用作备份。  
然后你就可以没有后顾之忧的对草稿进行修改了。