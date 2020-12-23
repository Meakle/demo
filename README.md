# 嗨！

嗨！欢迎你来到这里。

这里将会存放一些我自己做的一些小demo。



## demo01

> 我想了很久，都不知道该个这个demo取个什么名字，实在想不到了就直接叫demo吧（🤦‍♂️）。

### 思路

利用JS将CSS代码写入`style`标签中，并且在页面上显示`style`标签里面的内容。

为了炫酷，我利用JS的定时器，每隔一段时间写一点代码进去，而不是一次全部写进去。

这样就实现了页面的样式实时变化。



预览链接：👉 [点这里！](https://meakle.github.io/demo/demo01/index.html)



## simple-dom-library

我将一些原生的DOM操作封装了一层。可以更加简单的使用domAPI操作页面。

只是一个练习用的demo，对于dom的理解还不是很深，轮子造的肯定可以优化，但是还是想要造轮子

### 思路

在`window`对象上挂一个对象名为`dom`。在`dom`这个对象里面写一些函数，简化domAPI的操作。

比如：我要在一个节点都后面添加一个节点。原生的dom并没有给我们提供这个操作。

因此我封装了一个函数，用于在一个节点之前插入节点。

```js
dom.after = function(node, newNode){
    let parent = node.parentNode;
    return parent.insertBefore(newNode ,node.nextSibing);
}
```

项目地址：该仓库的`simple-demo-library`目录

## nav-demo

利用原生的JS和jQuery混合写的一个简单的导航。

能够实现搜索，增加收藏地址，删除收藏地址。

支持移动端和PC端

> PS：想用react重构这个项目

预览链接：👉 [点这里！](http://meakle.com/demo/nav-demo/src/index)

## simple-node-server

一个简单的静态服务器。

项目地址：该仓库的`simple-node-server`目录









