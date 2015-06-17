# BeamerForXidian
Mainly package for Xidian University‘s Beamer. Beamer theme based on Berkeley.

- Author: Stick Cui.
- E-mail: Stick_Cui@163.com
- Time: 2015/6/17
- Attention: Only can be used with XeLaTex.

###Copyright &copy; 2015 Stick Cui.

## 写在前面：

宏包CUMCMpackage为XeLaTeX环境下的宏包；使用时，请务必使用XeLaTex编译；否则会报错，导致无法使用！！！

## 使用说明：

###1、宏包引用

将**XDstyle.sty**文件以及**XDgraphics目录(含内部文件)**与自己所写的论文TeX源文件放到同一目录下；同时推荐在该目录下建立Image文件夹便于集中存放图片资源。

	\usepackage[control code]{XDstyle}
其中control code包括：English,CircleLogo,XDblue.

	English：英文风格
	CircleLogo：学校logo周围环绕为圆形。
	XDblue：PPT颜色改为西电蓝风格（默认为西电红风格，详见预览文件）。

###2、宏包title项设置：
	\title{} %PPT标题
	\subtitle{} %PPT子标题
	\institute{} %附加内容
	\author{} %作者
	\date{} %时间

###3、实用环境类

- 使用方法

		\begin{环境名}
		
		\end{环境名}
- 定理环境（仅介绍中文风格下）

		Th 定理
		Def 定义
		Lem 引理
		Cor 推论
		Prop 性质
		Eg 例
		Rem 注
		proof 证明

###4、字号

	\chuhao %初号     
	\xiaochuhao %小初号  
	\yihao  %一号     
	\erhao  %二号     
	\xiaoerhao  %小二号  
	\sanhao %三号     
	\sihao  %四号 
	\xiaosihao  %小四号  
	\wuhao  %五号     
	\xiaowuhao  %小五号  
	\liuhao %六号 
	\qihao  %七号

###5、表格使用参数

	L{自定义宽度}  %左对齐显示
	C{自定义宽度}  %居中显示
	R{自定义宽度}  %右对齐显示

###6、写在最后

具体使用样例，可以参考example.tex（英文风格见example_en.tex）文件；

预览文件：中文风格见example.pdf（西电蓝风格见example_XDblue.pdf）；英文风格见example_en.pdf（西电蓝风格见example_en_XDblue.pdf）

使用过程中，出现任何问题，可以给本人发邮件！！！

**注：**中文风格预览文件*.pdf在GitHub上直接预览可能会乱码（原因不详），可下载下来预览。
