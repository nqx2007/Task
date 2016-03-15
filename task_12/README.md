# 百度IFE的task12: 学习CSS 3的新特性

## 任务描述
 + 实现 [示例图](http://7xrp04.com1.z0.glb.clouddn.com/task_1_12_1.jpg) 中的几个例子
 + 实现单双行列不同颜色，且前三行特殊表示的表格
 + 实现正常状态和focus状态宽度不一致的input文本输入框，且鼠标焦点进入输入框时，宽度的变化以动画呈现
 + 不使用JavaScript，实现一个Banner图轮流播放的效果，且点击右下角的1，2，3可以切换到对应Banner图片



##我的实现[demo](http://ifetask.giantming.net/task_12/index.html)

 + 这个任务里面感觉其中比较优雅的实现是:
 第一个任务的table里面的tr的前三行红色的,所以我用了:`tr:nth-last-child(1n+8)`这样实现的,感觉还算优雅
 
 + 这个任务里的不好的实现
 最后一个任务有三个被隐藏的type="radio"的input和下面123是三个label关联起来的,用checked伪类实现点击,然后改图片的left值,感觉添加了无意义的标签,和没使用t3d那样的css3属性达到更好的动画效果这个实现不优雅

 + 有什么优雅实现望不吝赐教