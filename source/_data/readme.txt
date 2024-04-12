【自定义页面配色】
主题配色全部在 <root>/themes/shoka/source/css/_colors.styl 文件中，可以自行查看。

在 <root>/source/_data/ 目录新建文件 colors.styl ，在此文件中添改样式。

自定义 colors.styl 文件将覆盖主题默认样式，为了避免出错，请保证原有样式名均存在，在原有样式基础上进行增删改。

主题支持在 <root>/source/_data/ 目录建立三个自定义 styl 文件：

自定义文件名	     对应默认样式文件	    样式功能
colors.styl	       _colors.styl	          页面配色
iconfont.styl	       _iconfont.styl	          图标样式
custom.styl	       -	                          任意自定义样式