# MultipleSel
以控制器瘦身的方式实现的ableView、collectionView多选单选效果。
创建两个继承自NSObject的类Format、和Proxy
Format 负责业务逻辑
Proxy 负责处理tableView 、collectionView的代理方法。将
vc中的代码抽取出来。
![1单输入框](https://github.com/gjcbo/MultipleSel/raw/master/9.单输入框.gif)

