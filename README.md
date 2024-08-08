# OSG
OSG based 3D Earth application practical experiences

## 问题描述
使用`osg::ComputeBoundsVisitor`可以简单获取到模型的包围盒，然而由于是世界坐标，显示到球面上有明显的姿态问题，使用了旋转方法调整都不起作用

![微信图片_20240808161507](https://github.com/user-attachments/assets/1a1e4eee-7efe-41b0-9ab5-8cec659cc442)
![微信图片_20240808161519](https://github.com/user-attachments/assets/75506e22-234e-4027-a302-0fc39762c711)

## 解决方法
将每个顶点的

## 完整代码
```
void BouningBoxEffect::createEffect()
{
    

}
```
