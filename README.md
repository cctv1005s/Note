# TO DO LIST
1，完成华为的检测题

2，继续看校招的情况，选择一家投简历

3，写项目，看源代码，刷题（虽然到现在还没有刷题）


公司状况：

1，阿里 内推没戏

2，腾讯 内推等待

3，百度 内推等待

4，华为 笔试结束

5，今日头条 等待笔试

6，迅雷 等待

7，大疆 准备投递


2017年08月22日10:23:55
1，在本地实现权限控制
2，修改admin上面反馈的bug


```

阿里的模拟题目：

1，
一些具有操作记录的系统，如店铺装修、富文本编辑等，都具有undo/redo（撤销／恢复）功能，可实现界面操作过程的撤销和恢复。简述下由你来开发undo/redo功能的原理和思路。

2，利用面向对象思想完成买家信息删除功能，每一条买家信息包含
姓名 (name)
性别 (sex)
电话号码 (number)
省份 (province)
[](https://zos.alipayobjects.com/skylark/8814826a-f51c-46be-8fba-d07832ae1509/attach/7108/60f302d501bdd208/image.png)

实现以下要求
不能借助任何三方库，需使用原生代码实现
结合给出的基本代码结构，在下方2处 code here 处补充代码，完成买家信息的删除功能，注意此页面需要在手机上清晰显示。
js 代码可任意调整，例如可使用 es6 语法完成
提供基础代码结构
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <!--code here-->
  <title>demo</title>
  <style>
    * {
      padding: 0;
      margin: 0;
    }
    
    .head, li div {
      display: inline-block;
      width: 70px;
      text-align: center;
    }

    li .id, li .sex, .id, .sex {
      width: 15px;
    }

    li .name, .name {
      width: 40px;
    }

    li .tel, .tel {
      width: 90px;
    }

    li .del, .del {
      width: 15px;
    }

    ul {
      list-style: none;
    }

    .user-delete {
      cursor: pointer;
    }

  </style>
</head>

<body>
  <div id="J_container">
    <div class="record-head">
      <div class="head id">序号</div><div class="head name">姓名</div><div class="head sex">性别</div><div class="head tel">电话号码</div><div class="head province">省份</div><div class="head">操作</div>
    </div>
    <ul id="J_List">
      <li><div class="id">1</div><div class="name">张三</div><div class="sex">男</div><div class="tel">13788888888</div><div class="province">浙江</div><div class="user-delete">删除</div></li>
      <li><div class="id">2</div><div class="name">李四</div><div class="sex">女</div><div class="tel">13788887777</div><div class="province">四川</div><div class="user-delete">删除</div></li>
      <li><div class="id">3</div><div class="name">王二</div><div class="sex">男</div><div class="tel">13788889999</div><div class="province">广东</div><div class="user-delete">删除</div></li>
    </ul>
  </div>

<script>
// 此处也可换成ES6的写法
function Contact(){
    this.init();
}
	
// your code here 
</script>
</body>
</html>
```
