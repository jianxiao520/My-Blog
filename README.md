“Xus博客，是一个分享各种资源的博客。”


HTML结构：
index.html -> 【首页】  展示页: 展示Xus发表的文章以及一些Xus的个人介绍。
DailyShare.html - > 【今日分享】  分享页: 与博客相关，首页分享文章，今日分享页专注分享多媒体资源。
music.html -> 【音乐屋】 音乐播放: 在分享页点击试听音乐直接跳转到这音乐屋播放音乐。
Register.html - > 【登录&注册】 会员注册页: 登录以及注册写在一个页面方面新用户加入。


页面知识点：
【首页】 ：(页面主题:立体)
[导航栏]运用了图标字体，更清晰的使用户找到心仪的页面。
[文章列表]悬停运用了放大(scale)+阴影效果，使页面更具有立体感。
[自我介绍]悬停头像利用skewX配合动画修改图形变形达到头像像气泡一样抖动效果，使页面更有活力感。
[照片展示]运用了CSS3 3D的新特性preserve-3d展示图片，与列表呼应3D立体感。

【今日分享】 ：(页面主题:静)
[壁纸列表]悬停运用灰度(blur())使本来唯美的图片悬停后不失原来的优雅。
[电影列表]悬停运用移动(translate3d)+透明度(opacity)达到忽隐忽现飞出的效果。

【音乐屋】 ：(页面主题:唯美)
[唱片区域]运用了之前旋转的知识点。
[歌词展示]配合几句JS，使歌词滚动。
[媒体控制区]图标均为一张图片(精灵图)设置定位。
[进度条]配合JS获取媒体进度并改变width值达到进度条的简单效果。

【登录&注册】：
[轮播图]JS+CSS结合现实轮播图自动轮播与手动切页效果。
[登录注册]为了解决display: none;切换div死板问题，这里使用了z-index+过渡效果来达到div的切换。
[输入框]运用了伪元素，当为焦点时，控制在input框下的伪元素增加宽度来完成焦点动画。


缺点与改进：
1.没有完成 正文页 ，考虑到已经有几篇文章；过后改进自己的网页会增加相对于的文章正文页。
2.页面之间的跳跃比较大；
3.首页的3D图片展示区与首页有着些许违和感；没有美感概念的我不知如何调整。。
4.音乐盒的歌词只是被JS简单的控制着(修改top值)；需要歌词精确，要加入每句歌词的时间，JS进行分割并解析滚动。
5.样式的命名不统一，有时候命名为他的拼音，有时候则为英文，后面改又懒得去逐个修改┭┮﹏┭┮。

在线浏览：http://117.78.11.48:88/
http://39.99.234.162/
