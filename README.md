##zy-open
zy-open 是一个立志于帮助开发者提高开发效率的开源项目，会尽可能遵循以下理念及原则:
>1.可以作为简单项目的基础设施；</br>
>2.对大部分Android开发者都有用；</br>
>3.每一个功能、控件都有使用案例。</br>

###如何依赖？
>1.compile 'com.zy.open:lib:versionName'</br>
>2.目前最新 versionName 1.1</br>
>3.没了，你懂的</br>
>

###怎么联系我们？
QQ : 413700858 or 1454025171</br>
Email : 413700858@qq.com or GitHub163@126.com

###目前有些什么？
#####1.ZYActivity
博客：http://blog.csdn.net/neverwoods/article/details/52219642
基类Activity，可以自动保存传递过来的 bundle 对象，也就是 getIntent() 方法拿到的数据。然后呢？然后你再也不用担心因为内存被回收导致的空指针了，也不用每个 Activity 都去写保存 bundle 的代码了。除此以外还内置了显示和隐藏键盘的方法，至少我们是经常用到，各位客官呢？

#####2.ListAdapter、RecyclerAdapter
博客：<br>http://blog.csdn.net/neverwoods/article/details/52240294<br>http://blog.csdn.net/neverwoods/article/details/52386555<br>http://blog.csdn.net/neverwoods/article/details/52398587

你是否已经厌烦写 ListView、GridView 的适配器要写一大堆内容？还是早已对写 ViewHolder 类深恶痛绝？没关系，我们这里有一剂良药。继承我们的 Adapter，你大部分情况下只需要重写一个方法去渲染 item 的布局，其他的事情通通不用关心，甚至连 ViewHolder 都不用写，是不是很开心？
#####3.一些实用的工具类
比如 dp、sp、px 转换工具，比如图片压缩、旋转工具，比如 JSON 格式矫正工具

#####东西还不多，但是我们会继续努力完善，把这个项目做得越来越好，也希望各位能提供宝贵的意见。后续也会写点博客详细的讲讲，但是老鸟看 demo 应该就够了吧？
#####PS.不建议新手使用这个项目，这个项目能在某些方面帮助开发人员提高那么一丢丢的效率，但是对于新人来说正是学习的时候，跳过很多细节并不是什么好事


