<!DOCTYPE html>
<html lang="zh-cn">
<head>
	<meta charset="utf-8">
	<title>小小的世界</title>
</head>
<body>
	<div class="play">我是音乐,点我</div>
	<audio src="qby.mp3" id="myMusic"></audio>
	<script >
		var btn = document.getElementsByClassName("play")[0];
		var myMusic = document.getElementsById("myMusic");
		var onOff=true;
        btn.onclick = function();{
        	if (onOff) 
        	{
        		myMusic.play();
        		onOff=false;
        	}
        	else{
        		myMusic.pause();
        		onOff=true;
        	}
        	
        }
	</script>
	<h1>哇哈哈哈，俺是1.0</h1>
	<p>想必你已经见过俺滴弟弟2.0了吧</p>
	<p>按走的小清新风格，简约，内敛，沉静，大道至简</p>
	<h1>俺滴任务</h1>
	<p>那就是</p>
<p>求指教，俺这种音乐播不了（哭）是Js不对吗</p>
<img src="cuo.jpg">
<h3>超级建议点赞，看看会发生啥！！！！</h3>
<table>
	<td><img src="zan.bmp"></td>
	<td><img src="bi.bmp"></td>
	<td><img src="xing.bmp"> </td>

</table>
<buttom onclick=myFuction()>我是点赞按钮</buttom>
	    <script>
	        function myFuction(){
	            alert("谢谢屏幕前的大帅哥和大漂亮")
	        }
	    </script>
</body>
</html>
