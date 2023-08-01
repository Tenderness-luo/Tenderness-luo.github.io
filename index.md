## 欢迎来到姚的网站

<style>
        html:not([stylus-iframe]) body {
		background-image: none !important
	}
	html:not([stylus-iframe]) body:before {
		content: "";
		position: fixed;
		top: 0;
		right: 0;
		bottom: 0;
		left: 0;
		z-index: -100;
		background-image: url(https://res.lolicon.app/bilibili/bg.png);
		background-position: center bottom;
		background-size: cover;
		background-attachment: fixed;
		background-repeat: no-repeat;
	}
	@media screen and (max-width: 1650px) {
		html:not([stylus-iframe]) body:before {
			background-image: url(https://res.lolicon.app/bilibili/bg_small.png);
		}
	}
	.footer-wrp,
	.international-footer {
		background-color: transparent !important;
	}
</style>

### 音乐
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=2051317320&auto=0&height=66"></iframe>

### 视频
<iframe src="//player.bilibili.com/player.html?aid=80433022&bvid=BV1GJ411x7h7&cid=137649199&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width="100%" height="500"> </iframe>

### 图片
<img src="https://t.mwm.moe/pc">
<div id="image-container"></div>

<script>
	// API请求URL
	const apiUrl = 'https://api.lolicon.app/setu/v2?excludeAI=true';

	// 使用fetch请求API数据
	fetch(apiUrl)
	.then(response => response.json())
	.then(data => {
	// 从返回值中提取图片地址
	const imageUrl = data.data[0].urls.original;

	// 创建一个img标签来显示图片
	const imgTag = document.createElement('img');
	imgTag.src = imageUrl;

	// 将img标签添加到页面中的image-container div中
	const imageContainer = document.getElementById('image-container');
	imageContainer.appendChild(imgTag);
      })
	.catch(error => console.error('发生错误：', error));
</script>

### 一言
<span id="jinrishici-sentence"></span>
<script src="https://sdk.jinrishici.com/v2/browser/jinrishici.js" charset="utf-8"></script>  

### 友情链接  
[冬優ちゃん](https://fuibafuyu.net/)  
[纳兰音韵](https://nalanyinyun.top/)  
[神代綺凛の随波逐流](https://moe.best/) 
[次元api](https://t.mwm.moe/) 
[小工具箱](https://lolicon.dev/) 

### 笑话
“我手机不开机了咋整啊”  
“什么表现，怎么搞的，你最近干什么了”  
“我不到啊，手机放那自己砖了”    

### COVID-19 新型冠状病毒 信息统计
<iframe src="https://cn.bing.com/covidans/widget?&setlang=zh-CN&lcid=/TaiWan&mt=Map" height="545" frameborder="no" scrolling="no" border="0" width="100%"> </iframe>   
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议</a>进行许可。

<div align="center"><img style="border-radius: 8px" src="https://api.puresys.net"></div>
