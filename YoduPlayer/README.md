# YoduPlayer

一款支持 instantclick 或者 pjax 的背景音乐播放器插件（typecho博客插件）

> 2018,05,28，默认音量调低，默认歌曲链接换掉，之前的死了，多皮肤机制公开手动选择

> 2018,02,27，优化列表播放选中样式，增强兼容性，同时适配未来yodu模板5版本系列

> 2018,02,25，新增随机播放功能，简单优化，yodu定制皮肤会根据模板自动勾选

> 2017,12,10封面图404时，自动将内置图片补上去假装图没挂，播放器外面点击关闭抽屉，优化yodu模板的定制皮肤，版本号1.8.0

> 2017,12,6增加默认音乐与封面图（内置音乐只要非盈利性质则不涉及版权问题），版本号1.7.5

> 2017,10,9正在播放的歌曲在列表中标注出来，版本号1.7.3

> 2017,10,8歌曲列表功能跟进，版本号1.7测试版

> 2017,10修复部分浏览器兼容问题

> 2017,9修复部分浏览器进度条错位问题

> 2017,07,25解决部分模板的字体冲突问题

> 2017,07.10重新加入修复版的网易音乐获取 api，版本号 1.2.0。

> 2017,06.12诈尸更新，支持显示音乐播放进度条

> 1，支持自定义播放器css

> 2，支持显示歌曲名称，歌手，封面等

> 3，针对typecho的Yodu主题模板特殊优化，根据期多皮肤自动变色适应皮肤等

> 4，无 JQ，要求浏览器 ie9+。（大概）【发现欧朋浏览器不兼容】

**使用方法**

下载压缩包, 解压，得到名为YoduPlayer的文件夹，如果不是请将文件夹重命名为YoduPlayer，之后上传到你博客中的 /usr/plugins 目录，在后台启用即可

插件后台配置歌曲格式: 

{title:"xxx", artist:"xxx", cover:"http:xxxx", mp3:"http:xxxx",cover:"图片地址",} ，每个歌曲之间用英文,隔开。

**请保证歌曲列表里至少有一首歌**！

