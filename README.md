A/B需求应该是操作有误，a需求并没有合并到dev，远程有本地一直没有

![img.png](img.png)

cherrypick可以挑选几个功能合并，不用全部合并

rebase可以在冲突的时候用，让合并变成一条线

如果出错可以先revert然后再提交

推代码前一般先拉