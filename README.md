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
<p>可以多点几次哦</p>
<table>
	<td id="control"><img src="zan.bmp"></td>
	<td><img src="bi.bmp"></td>
	<td><img src="xing.bmp"> </td>

</table>
<script >
	var e,i;
	e=document.getElementsById("control")
	i=0;
	e.onclick=function(){
		if(i==0){
			alert("谢谢屏幕前的大帅哥，还有大漂亮")；
			i++;
		}if(i==1){
			alert("点赞的各位父老乡亲们，出门捡到钱")；
			i++
		}if(i==2){
			alert("点赞的各位父老乡亲们，游戏不掉线")；
			i++
		}if(i==3){
			alert("点赞的各位父老乡亲们，活到一万岁")；
			i++
		}else{
			alert("施主，真没了")；
			i=0；
		}
		return false;
	}
</script>
</body>
</html>
