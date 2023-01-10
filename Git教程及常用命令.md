- 要明白这3个概念，工作区（**working tree**），暂存区（**index /stage**），本地仓库（**repository**）
- git跟不同的参数，比较不同的区间的版本。

1. git diff：是查看working tree与index的差别的。
2. git diff --cached：是查看index与repository的差别的。
3. git diff HEAD：是查看working tree和repository的差别的。其中：HEAD代表的是最近的一次commit的信息。

 **综上所述：git diff 后面跟文件名称是是查看工作区（working tree）与暂存区（index）的差别的。**





**答疑: **

LF是linux下的换行，CRLF是Windows下的回车换行，用Git bash 模拟的linux环境，会默认把Windows下的回车换行直接替换成换行，可以不用管