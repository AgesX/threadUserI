# ui_thread
学习卡顿



<hr>



<hr>



<hr>



<hr>


```

/** Class representing a timer bound to the display vsync. **/
@available(iOS 3.1, *)
open class CADisplayLink : NSObject {


```



<hr>



<hr>

解决:


预排版线程, 布局、层级、和渲染信息、模型数据


多线程，解决一切


富文本


图片解码


计算高度


UI 的布局



<hr>

解决，就是代码变多


程序性能，与开发效率

<hr>

减少 UI 显示层面，不必要的工作



<hr>



<hr>


使用代码，取代 xib



<hr>



<hr>


<hr>



<hr>


子线程，不能操作 UI 的什么？


为了避免，数据竞争


> 数据竞争, 导致显示失控


<hr>


<hr>
<hr>


<hr>


YYAsyncLayer

Texture

抛弃了 UIKit


<hr>

<hr>


<hr>


Graver

一张位图，

搞定所有的控件


<hr>


Graver


子线程绘制出，一张位图，


赋值到 CALayer 的 contents


