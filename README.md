# similiar_image_algorithm

-----
相似图片搜索的原理

这里的关键技术叫做"感知哈希算法"（Perceptual hash algorithm），它的作用是对每张图片生成一个"指纹"（fingerprint）字符串，然后比较不同图片的指纹。结果越接近，就说明图片越相似。

http://www.ruanyifeng.com/blog/2011/07/principle_of_similar_image_search.html

http://www.ruanyifeng.com/blog/2013/03/similar_image_search_part_ii.html

http://www.isnowfy.com/similar-image-search/

----
相似图片搜索的三种哈希算法

http://blog.csdn.net/zmazon/article/details/8618775

http://www.phash.org/download/


http://www.cnblogs.com/technology/archive/2012/07/12/2588022.html

----
http://blog.sina.com.cn/s/blog_5ddc071f0101o9th.html

'''import com.sun.image.codec.jpeg.JPEGCodec;
在Eclipse中处理图片，需要引入两个包：
import com.sun.image.codec.jpeg.JPEGCodec;
import com.sun.image.codec.jpeg.JPEGImageEncoder;
报错:
Access restriction: The type JPEGImageEncoder is not accessible due to restriction on required library C:\Java\jre1.6.0_07\lib\rt.jar'''


'''此时解决办法：
Eclipse默认把这些受访问限制的API设成了ERROR。只要把Windows-Preferences-Java-Complicer-Errors/Warnings里面的Deprecated and restricted API中的Forbidden references(access rules)选为Warning就可以编译通过。'''

