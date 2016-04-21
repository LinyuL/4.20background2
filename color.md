# 颜色和透明度

css中颜色表示方式：
1、rgb(0-255,0-255,0-255)
2、#000000   十六进制
3、关键词  red blue green
4、rgba(0-255,0-255,0-255,0-1)
	可以让文字颜色、背景颜色、变成透明

background:tranparent
opacity:0-1;  表示透明度
filter：Alpha(opacity=0-100);  ie滤镜

-浏览器前缀

火狐浏览器  -moz-
IE   		-ms-
chrome   	-webkit-
欧鹏  		-o-

-模糊效果：
-webkit-fliter:blur(10px);

-灰度效果
-webkit-fliter:blur(0);