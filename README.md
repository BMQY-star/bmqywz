<!doctype html>
<html lang="zh_CN">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,minimum-scale=1,maximum-scale=1,initial-scale=1,user-scalable=no" />

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css" integrity="sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS" crossorigin="anonymous">
    <style>
    .active{background-color:DeepSkyBlue;}
    .table{background-color:Black;color:White;box-shadow:0px 7.5px 5px #606060;}
    .normal{background-color:Black;}
    .active_page{display:block;}
    .normal_page{display:none;}
    .dh_text{font-size:120%;}
    .url{color:Blue;}
    .i_kj{width:100%;height:500px;}
    .jiance{display:none;}
    .zs_shadow{
    box-shadow:0px 0px 10px Red;
    background-color:Red;
    color:Gold;
    border:0;
    }
    </style>
    <title>BMQY工作室</title>
  </head>
  <body>
<script>
load_error.className = "normal_page";
function dh(id) {
	kj.src = ""; //浏览框关闭
	home.className = "normal";//主页
	home_page.className = "normal_page";
	application.className = "normal";//应用程序
	application_page.className = "normal_page";
	article.className = "normal";//文章
	article_page.className = "normal_page";
	other.className = "normal";//其他
	other_page.className = "normal_page";
	catchus.className = "normal";//联系
	catchus_page.className = "normal_page";
	document.getElementById(id).className = "active";
	document.getElementById(id + "_page").className = "active_page";
}
function openurl(url) {
	self.location.href = url;
}
</script>
	<div class="table">
	  <table border=1 width=100%>
		<tbody>
		  <tr>
			<td id="home" class="active" onclick="dh(this.id)"><center><a class="dh_text">首页</a></center></td>
			<td id="application" onclick="dh(this.id)"><center><a class="dh_text">应用</a></center></td>
			<td id="article" onclick="dh(this.id)"><center><a class="dh_text">文章</a></center></td>
			<td id="other" onclick="dh(this.id)"><center><a class="dh_text">工具</a></center></td>
			<td id="catchus" onclick="dh(this.id)"><center><a class="dh_text">联系我们</a></center></td>
		  </tr>
		</tbody>
	  </table>
	</div>
	<div style="background-color:Gray;color:White;display:none">
	  <h4 id="wz">当前位置:<button onclick="test()">首页</button></h4>
	</div>
	<div id="home_page" class="active_page">
	  <h1>BMQY工作室</h1>
	  <p>BMQY工作室，由一些APP Inventor2爱好者组成，如果你也对此有兴趣，你也可以加入我们工作室！</p>
	  <img src="http://www.bmqyschcjy.xyz/3360c0ca661cf144.jpg" width=100%>
	  <br><br><br><br>
	  <div>
		<center>
		  <label class="zs_shadow" onclick="openurl('https://www.xcgzs.ml/zanshang')"><h3>赞赏</h3></label>
		</center>
	  </div>
	</div>
	<div id="application_page" class="normal_page">
	  <h1>工作室应用|<a href="/app/index.html">投稿</a></h1>
	  <ul>
		<li><h2>安卓应用:</h2></li>
		<ul>
		  <li><h3 class="url" onclick="openurl('https://www.xcgzs.ml/application/Fruit')">Fruit水果配对</h3></li>
		  <li><h3 class="url" onclick="openurl('https://www.xcgzs.ml/application/jsq')">计算器</h3></li>
		  <li><h3 class="url" onclick="openurl('https://www.xcgzs.ml/totl')">关闭所有灯</h3></li>
		  <li><h3 class="url" onclick="openurl('http://t.cn/Ai8NOA1c')">摇一摇打开相机</h3></li>
		</ul>
		<li><h2>html小程序:</h2></li>
		<ul>
		  <li><h3 class="url" onclick="openurl('https://html.xcgzs.ml/csz')">猜数字</h3></li>
		  <li><h3 class="url" onclick="openurl('https://html.xcgzs.ml/jsq')">计算器</h3></li>
		</ul>
	  </ul>
	</div>
	<div id="article_page" class="normal_page">
	  <h1>文章:</h1>
	  <ul>
		<li><h2>教程</h2></li>
		<ul>
		  <li><h3 class="url" onclick="alert('抱歉，该页面暂时无法访问！')">怎样编写aix</h3></li>
		  <li><h3 class="url" onclick="openurl('/sdk/index.html')">Android SDK版本对应表</h3></li>
		  <li><h3 class="url" onclick="openurl('/vtp')">VB和Python语法对照</h3></li>
		</ul>
	  </ul>
	</div>
	<div id="other_page" class="normal_page">
	  <h1>工具</h1>
	  <ul>
		<li><h2>在线工具:</h2></li>
		<ul>
		  <li><h3 class="url" onclick="openurl('http://www.javadecompilers.com/apk')">APK反编译</h3></li>
		  <li><h3 class="url" onclick="openurl('https://demo.glyptodon.com/')">Windows虚拟机</h3></li>
		  <li><h3 class="url" onclick="openurl('https://www.jb51.net/tools/html_jiami.htm')">html源代码加密</h3></li>
		</ul>
	  </ul>
	</div>
	<div id="catchus_page" class="normal_page">
	  <h1>联系我们</h1>
	  <ul>
		<li><h2>与我们交谈:</h2></li>
		<ul>
		  <li><h3 class="url" onclick="self.location.href = ('https://jq.qq.com/?_wv=1027&k=5KQLy8M')">加入官方群</h3></li>
		  <li><h3 class="url" onclick="self.location.href = ('https://jq.qq.com/?_wv=1027&k=5ZCvEfv')">加入备用群</h3></li>
		  <li><h3 class="url" onclick="self.location.href = ('https://jq.qq.com/?_wv=1027&k=5ZCvEfv')">欢迎加入我们</h3></li>
		</ul>
		<li><h2>友情链接</h2></li>
		<ul>
		  <li><h3 class="url" onclick="self.location.href = ('https://www.qyzz.ml')">起源之战工作室官网</h3></li>
		  <li><h3 class="url" onclick="self.location.href = ('https://www.freenom.com')">免费域名提供商(可能要翻墙暂时无法使用)</h3></li>
		  <li><h3 class="url" onclick="self.location.href = ('https://www.github.com')">免费空间</h3></li>
		</ul>
	  </ul>
	</div>
	<iframe src="" id="kj" frameborder=0 class="normal_page"></iframe>
  </body>
</html>
