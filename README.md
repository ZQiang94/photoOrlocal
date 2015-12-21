# photoOrlocal
#####mail : 452608069@qq.com || zhangqiang452608069@gmail.com<br>
#####weibo : http://weibo.com/u/3174082744<br>
#####欢迎交流Android开发技术~<br>
###弹窗选择本地或相机图片(来源:OSChina)<br>
<br>
这个demo本来是帮一个朋友解决的一个问题，问题是这样的：在一般的机器中是可以正常选择图片并展示，
但是在红米手机上会出现崩溃的情况，因为之前一直比较OSChina客户端，在OSC中也有类似功能，于是就看了
一下OSC客户端的源码，内部实现除了对内存卡的判断，还有对sdk版本的适配，做的比较合理，就原封的将内
部的源码摘取出来，感觉这种实现方式比较合理，其中，我们在对内存卡的读写，有一部分人喜欢对sdcard1读
写，但是现在的手机大都没有手动插入的sdcard，直接是内置存储卡，这种存储卡在程序中默认为sdcard0（不
敢保证所有的机型都是这样），所以有的人在读写sdcard1的时候会有异常。
以上都是我个人见解，有理解不对的可以通过上面的联系方式，QQ或是其他来纠正。欢迎欢迎~~

[image]{https://raw.githubusercontent.com/ZQiang94/photoOrlocal/master/pic01.png}<br>
[image]{https://raw.githubusercontent.com/ZQiang94/photoOrlocal/master/pic03.png}<br>
