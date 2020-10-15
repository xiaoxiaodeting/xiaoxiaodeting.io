<!DOCTYPE html>
<html lang="zh-cn">
<head>
	<meta charset="utf-8">
	<title>小小的世界</title>
</head>
<body>
	<div class="music">我是音乐,点我</div>
	<audio src="qby.mp3" id="myMusic"></audio>
	<script >
		var btn = document.getElementsByTagName("music")[0];
		var myMusic = document.getElementsByTagName("myMusic");
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
	<h1>俺是1.0</h1>
	<p>想必你已经见过俺滴弟弟2.0了吧</p>
	<p>俺走的小清新风格，简约，内敛，沉静，大道至简</p>
	<h1>俺滴任务</h1>
	<p>那就是</p>
<p>求指教，俺音乐播不了（哭）是Js不对吗</p>
<img src="t.jpg">
</body>
</html>
