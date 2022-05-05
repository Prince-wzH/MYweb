<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>华宇学子登记网站</title>
<style type="text/css">

#body{ width:658px; height:800px;background-image:url(images/1.webp); background-repeat:no-repeat;opacity:0.7; margin:0 auto; position:relative; border-radius:30px}

.font{text-align:left;font-family:"黑体"; position:absolute;top:50px; left:175px; font-size:18px; color:#000;}

.top{width:30px; height:30px; background-color:#000; position:absolute; right:320px;border-radius:50%; box-shadow:2px 1px 1px 2px #333333 inset}
.botton1{ width:50px; height:30px;background:#9CF; border-radius:10%}
body {
	background-color: #FFF;
}
</style>
</head>

<body>
<div id=body >
<div class="top"></div>
<div class="font">
<form action="#" method="post">
<h1>华宇学子登记表</h1>
<table width="658" border="0" cellspacing="2" cellpadding="2">
  <tr>
    <td><p><span>用户登录名:</span>
<input type="text" name="n1" value="myemail@163.com" disabled readonly></p></td>
  </tr>
  <tr>
    <td><p><span>真实姓名:</span>
<input name="n2" type="text" autofocus required placeholder="例如：王子豪" pattern="^[\u4e00-\u9fa5]{0,}$" size="10"></p>
</td>
  </tr>
  <tr>
    <td><p><span>真实年龄:</span>
<input type="number" name="old" value="20" min="18" max="24"  step="1" required></p>
</td>
  </tr>
  <tr>
    <td><p><span>出生日期:<span>
<input type="date" name="date1" value="2002-1-25" required></p></td>
  </tr>
  <tr>
    <td><p><span>电子邮箱:</span>
<input type="email" name="e1" placeholder="1619065381@qq.com" required multiple></p></td>
  </tr>
  <tr>
    <td><p><span>身份证号:</span>
<input name="id" type="text" required pattern="^\d{8,18}|[0-9x]{8,18}|[0-9x]{8,18}?$" size="30"></p>
</td>
  </tr>
  <tr>
    <td><p><span>电话号码:</span>
<input type="tel" name="t1" required pattern="^\d{11}$"></p>
</td>
  </tr>
  <tr>
    <td><p><span>个人主页:</span>
<input type="url" name="y1" list="urllist" placeholder="http://www.baidu.cn"  required pattern="^http//([\w-]+\.)+[\w-]+(/w-./?%&=] *)?$">
<datalist id="urllist">
<option>http://www.baidu.cn</option>
<option>http://www.itcast.cn</option>
<option>http://www.360.cn</option></datalist>
</p></td>
  </tr>
  <tr>
    <td><p><span>幸运色:</span>
<input type="color" name="c1" value=""></p></td>
  </tr>
  <tr>
    <td><p><input type="submit" class="botton1" value="提交" >
<input type="reset" class="botton1" value="重置"></p></td>
  </tr>
</table>
</form>
</div>
</div>
</body>
</html>
