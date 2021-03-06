# 总结表单优化的几个点

## 表单应该只有一列
多列布局会扰乱用户垂直方向的视线移动

## 把标签与输入框成组排列
把标签和输入框贴近排列，确保项目之间留有足够的高度，防止用户迷惑

## 避免全大写标签
全大写标签更难阅读和浏览，应大小写结合来命名

## 如果选项小于6个，全部展示出来
把选项放入下拉菜单需要用户进行两次点击，还会把选项隐藏起来
如果超过5项使用下拉选框
如果超过选项25个，就要在下拉菜单中加入搜索

## 纵向排列勾选框（和单选框）以保证易读性
纵向排列勾选框可以加快勾选速度

## 行动指令要具有描述性
比如提交按钮不要用 submit，要描述出具体行为，比如登录，即为 sign up

## 逐行说明错误
告诉用户哪里错了，尽早的提示

## 逐行验证要在用户填完一行之后进行
除非填写中验证更有帮助

## 用输入框长度来反映内容
输入框的长度暗示了答案的长度。对于字数固定的输入框，例如电话号码、邮政编号等

## 把相关信息编组
用户分块思考，更容易理解表单

## 合理化表单结构
使用label表示字段文本，添加必要的for属性，以在点击字段文本时，文本框能获得焦点
文本框不使用size属性定义宽度，而使用css的width属性
添加maxlength属性限制输入字符的长度
