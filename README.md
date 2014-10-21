Readme.txt
==========
针对中文,演示Markdown的各种语法
  
大标题
===================================
	大标题一般显示工程名,类似html的\<h1\><br />
	你只要在标题下面跟上=====即可
![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/1.png "大标题")
***
中标题
-----------------------------------
	中标题一般显示重点项,类似html的\<h2\><br />
	你只要在标题下面输入------即可
![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/2.png "中标题")
***
### 小标题
	小标题类似html的\<h3\><br />
	小标题的格式如下 ### 小标题<br />
	注意#和标题字符中间要有空格
![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/3.png "小标题")<br/>
***
	
### 注意!!!下面所有语法的提示我都先用小标题提醒了!!! 

### 单行文本框
	这是一个单行的文本框,只要两个Tab再输入文字即可
![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/4.png "单行文本框")
***

        
### 多行文本框  
	这是一个有多行的文本框
	你可以写入代码等,每行文字只要输入两个Tab再输入文字即可
	这里你可以输入一段代码
![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/5.png "多行文本框")
*** 


### 比如我们可以在多行文本框里输入一段代码,来一个Java版本的HelloWorld吧
    public class HelloWorld {

      /**
      * @param args
	    */
	    public static void main(String[] args) {
		    System.out.println("HelloWorld!");

	    }

    }
### 链接
1.[点击这里链接到www.google.com](http://www.google.com)<br/>
2.[点击这里链接到百度](http://www.baidu.com)<br/>
![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/11.png "链接")
*** 


### 只是显示图片
![github](https://avatars1.githubusercontent.com/u/8358898?v=2&s=460 "github")

![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/6.png "图片")
*** 


### 想点击某个图片进入一个网页,比如我想点击github的icorn然后再进入www.github.com
[![image]](http://www.github.com/)
[image]: https://avatars1.githubusercontent.com/u/8358898?v=2&s=460 "github"

![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/7.png "链接图片")
*** 

### 文字被些字符包围
> 文字被些字符包围
>
> 只要再文字前面加上>空格即可
>
> 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
> 但> 只能放在行首才有效

![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/8.png "包围")
*** 


### 文字被些字符包围,多重包围
> 文字被些字符包围开始
>
> > 只要再文字前面加上>空格即可
>
>  > > 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
>
> > > > 但> 只能放在行首才有效

### 特殊字符处理
有一些特殊字符如<,#等,只要在特殊字符前面加上转义字符\即可<br />
你想换行的话其实可以直接用html标签\<br /\>

![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/9.png "多重包围")
***
	
* 在行首加点
行首输入*，空格后输入内容即可

![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/10.png "行首加点")
*** 
	
	
<ol>
<li>Bird</li>
<li>McHale</li>
<li>Parish</li>
</ol>

![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/12.png "html")
	
***
	
*single asterisks*
![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/13.png "html")

***

**double asterisks**
![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/14.png "html")

***

`printf()`
```
test
```
![image](https://raw.githubusercontent.com/Zx7ffa4512/MD-File-Syntax/master/pic/15.png "html")

***

