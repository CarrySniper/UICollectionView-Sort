# UICollectionView-Sort
UICollectionView 实现单元格拖拽移动排序

区分iOS9前后，使用UICollectionView及其代理方法。iOS9之后有自带方法可以实现该效果，只需添加长按手势，实现手势方法和调用iOS9的Api交换数据；iOS9之前需要自己写方法实现这效果，除了要添加长按手势，这里还需要利用截图替换原理，手动计算移动位置来处理视图交互和数据交互。

百度经验 http://jingyan.baidu.com/article/19020a0a153872529d28421a.html

 ![](https://github.com/cjq002/UICollectionView-Sort/raw/master/Media/vedio.gif) 
