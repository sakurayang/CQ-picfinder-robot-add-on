# CQ-picfinder-robot-add-on

给Tsuk1ko大佬的CQ-picfinder-robot做了几个自用小挂件
基本是稳定的，有bug但是没时间修


##部件列表
###1.涩图分类
可以请求不同种类的涩图，数据库为本地储存的MongoDB，可以用pxer扒

###2.自动获取新微博
定时检查指定账号是否有发新微博，如果有就自动发出来，包含文字图片和视频，
从微博移动版获取的内容，无需登录但是需要找你想看的人的uid，countainerID = 107603+uid（也不知道为什么加107603就管用）
可以用特定语句开启或者关闭，偶尔会抽风

###3.看漫画
实现了自动翻页，暂停自动翻页，跳页，手动翻页之类的功能
可以和狗群员一起看漫画，没什么卵用

###4.获取少前新人/皮肤的大破图
来源是少前台服官网，需要手动触发

###5.骰子
可以扔出任意面数（<1000），任意个数(<10)的骰子，可以指定最小值，自动统计总分
（最开始偷懒直接写main里面了）

###6.少前战区分数统计(能用，有bug，几率报错)
也用了MongoDB...可以输入分数然后查看分数（写了一半！）
@机器人然后用以下格式
战区 游戏名称:xxxx；分数：xxxxxx；排行：xx
（不用打百分号，注意用分号隔开每项内容）
