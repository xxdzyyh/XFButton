# XFButton

在使用UIButton的时候，默认是图片在左边，文字在右边。想要修改图片和文字的位置，可以通过设置Title insets和Image inserts来实现，个人感觉还是比较麻烦的。

直接继承UIButton,重载
  
    - (void)layoutSubviews 

和 
  
    - (CGSize)intrinsicContentSize 
会相对简单灵活。重载layoutSubviews可以设置直接按钮图片和文字的位置，而intrinsicContentSize这个方法或被系统或者其他的地方使用到，需要提供一个正确的值。

简书地址：<http://www.jianshu.com/writer#/notebooks/2698290/notes/6795956>
