# 十大经典排序算法动画，看我就够了！

**Tip** 为了演示更加清楚，本文中所有的动画都放慢了速度，因此GIF大小对比之前会有所增大，图片加载速度会变慢，如果你想获取所有的超清动画，在公众号 **五分钟学算法**回复 **github** 可获得资料。

> 在前面的章节中详细的讲解分析了十大经典排序算法，本文将进行一个大总结同时分析它们的时间复杂度与稳定性。


**排序算法是《数据结构与算法》中最基本的算法之一。**

排序算法可以分为**内部排序**和**外部排序**。

内部排序是数据记录在内存中进行排序。

而外部排序是因排序的数据很大，一次不能容纳全部的排序记录，在排序过程中需要访问外存。

常见的内部排序算法有：插入排序、希尔排序、选择排序、冒泡排序、归并排序、快速排序、堆排序、基数排序等。

用一张图概括：

![image](http://upload-images.jianshu.io/upload_images/1940317-7caf7a8dec095a80.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 关于时间复杂度：

1. 平方阶 (O(n2)) 排序 各类简单排序：直接插入、直接选择和冒泡排序。
2. 线性对数阶 (O(nlog2n)) 排序 快速排序、堆排序和归并排序；
3. O(n1+§)) 排序，§ 是介于 0 和 1 之间的常数。 希尔排序
4. 线性阶 (O(n)) 排序 基数排序，此外还有桶、箱排序。


#### 关于稳定性：

1. 稳定的排序算法：冒泡排序、插入排序、归并排序和基数排序。

2. 不是稳定的排序算法：选择排序、快速排序、希尔排序、堆排序。




### 1. 冒泡排序
![image](http://upload-images.jianshu.io/upload_images/1940317-fafcf49997d511ee.gif?imageMogr2/auto-orient/strip)
### 2. 选择排序
![image](http://upload-images.jianshu.io/upload_images/1940317-b69f69ee21073f80.gif?imageMogr2/auto-orient/strip)
### 3. 插入排序
![image](http://upload-images.jianshu.io/upload_images/1940317-9455ff13bc8fbdc6.gif?imageMogr2/auto-orient/strip)
### 4. 希尔排序
![image](http://upload-images.jianshu.io/upload_images/1940317-acc6c6f16b096794.gif?imageMogr2/auto-orient/strip)
### 5. 归并排序
![image](http://upload-images.jianshu.io/upload_images/1940317-d3d400686bc61c30.gif?imageMogr2/auto-orient/strip)
### 6. 快速排序
![image](http://upload-images.jianshu.io/upload_images/1940317-6d01faf07a21e730.gif?imageMogr2/auto-orient/strip)
### 7. 堆排序
![image](http://upload-images.jianshu.io/upload_images/1940317-64e671a84ec27769.gif?imageMogr2/auto-orient/strip)
### 8. 计数排序
![image](http://upload-images.jianshu.io/upload_images/1940317-ea11a52dedaf0795.gif?imageMogr2/auto-orient/strip)
### 9. 桶排序
![image](http://upload-images.jianshu.io/upload_images/1940317-3d1c77fe4c71ce1a.gif?imageMogr2/auto-orient/strip)
### 10. 基数排序
![image](http://upload-images.jianshu.io/upload_images/1940317-28a71f3fdbd60b9e.gif?imageMogr2/auto-orient/strip)
