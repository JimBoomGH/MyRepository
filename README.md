# MyRepository

hashmap: https://www.cnblogs.com/yuanblog/p/4441017.html

安卓异常跟踪：Bugly

内存缓存，本地缓存，linkedhashmap原理：https://blog.csdn.net/qq_15893929/article/details/85229364

动画入门和进阶文章列表：https://blog.csdn.net/u010126792/article/details/85340010

安卓热修复：https://www.jianshu.com/p/e71ac5dfecbd

安卓开源项目：http://p.codekk.com/detail/Android/lizhifeng-sky/VideoEdit

网络框架okhttp:https://blog.csdn.net/xx326664162/article/details/77714126

面试必看
 类的加载过程：https://www.cnblogs.com/fanjie/p/6916784.html
 
 安卓的内存机制，堆栈:https://www.cnblogs.com/lcw/p/3942218.html
 
 复习大纲：https://github.com/JimBoomGH/android_interview     https://github.com/JimBoomGH/LearningNotes
 
 binder机制，app启动流程，两个activity跳转的生命周期：oncreat-onstart-onresunme  onpause onrestart-onstart-onresunme onstop-ondestroy
 Handler，Looper, Message：handler发送消息，looper循环遍历消息队列，message消息
 
 子线程使用handler:在创造hander前Looper.prepare()，创造完后Looper.loop()，1、Looper.prepare()是给这个Thread创建Looper对象，一个Thead只有一个Looper对象。2、Looper对象需要一个MessageQueue对象一个Looper实例也只有一个MessageQueue。3、调用Looper.loop();  不断遍历MessageQueue中是否有消息。4、Handler 作用是发消息到MessageQueue，从而回掉Handler 的HandleMessage的回掉方法。
 
 app如何适配   多分辨率适配：https://www.jianshu.com/p/ec5a1a30694b   
 一种分辨率使用一个dimens，包含dimens生成器:https://blog.csdn.net/github_2011/article/details/72636851
 
 dcl单例
 debug与release
 软引用弱引用
 设计模式：观察者，单例
 Handler机制
 app适配
 View的绘制流程
 string stringbuffer stringbuilder
 并发  各种锁
 hashmap arraymap sparsemap
 stratservice bindservide
 view的生命周期
 listview多种item的缓存  实现不同type item的管理
 
 安卓6.0新特性：动态权限   8.0:画中画，通知
 
 线程池的的核心线程数：每秒执行的线程数/ tasks/(timeout/taskcost) //每秒要执行的任务数/（超时时间/每个任务的执行时间）
 
 类的初始化顺序：静态变量，静态代码块，构造方法
 
 自定义view及事件冲突
 
 事件分发机制
 
 Binder机制 https://blog.csdn.net/lijizhi19950123/article/details/77920054
 
 
 Android中进程的级别，以及各自的区别。（前台进程，可见进程，服务进程，后台进程）
 
 线程池的相关知识。（线程池结合lrucash先从内存中加载，然后从硬盘加载，最后再从网络下载，制作图片缓存框架）
 
 ① 必须在UI线程中创建AsyncTask的实例.

② 只能在UI线程中调用AsyncTask的execute方法.

③ AsyncTask被重写的四个方法是系统自动调用的,不应手动调用.

④ 每个AsyncTask只能被执行(execute方法)一次,多次执行将会引发异常.

⑤ AsyncTask的四个方法,只有doInBackground方法是运行在其他线程中,其他三个方法都运行在UI线程中,也就说其他三个方法都可以进行UI的更新操作.
 
 内存泄露，怎样查找，怎么产生的内存泄露。
 
 Android优化，性能优化(ui卡顿 流畅性（加载快，异步，分步，多线程）稳定性 anr oom crash)，布局优化，高性能编码优化
 
 怎样计算一张图片的大小，加载bitmap过程（怎样保证不产生内存溢出），二级缓存，LRUCache算法，三级缓存。
 
 mvp设计模式
 
 launchmode
 
 生命周期，加载方式
 
 多线程 线程池
 
简历导向：

 音视频编解码  自定义view list（分批加载，分页显示） list recycleview区别（缓存，刷新，下拉，head foot） 事件分发 okhttp 三级缓存 glide udp tcp ormlite  内存泄漏 anr  
 
百度面试：https://blog.csdn.net/kisty_yao/article/details/79447579
