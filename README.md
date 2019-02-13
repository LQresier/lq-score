# lq-score
### 基于jquery的星级打分插件

使用方法和使用demo请看：**demo.html**，里面有详细的注释

### 属性参数介绍：

1.$tipEle--------提示元素，请传入jquery对象

2.fontSize-------大小，字符串类型

3.isReScore------是否允许重新评分

4.tips-----------提示，可以是default默认消息，可以传模板字符串，也可以传长度为5的数组

5.zeroTip--------无分数提示，字符串类型

6.score----------分数，小数、整数都可以

7.callBack-------评分回调，会返回分数和插件元素李，例：function(score,ele){}

8.content--------内容

9.defultColor----默认颜色(未选中的颜色)

10.selectColor----选中后的颜色，可以传单个字符串，也可以传长度为5的数组
