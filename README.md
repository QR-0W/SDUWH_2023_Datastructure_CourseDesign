# 山东大学（威海）数据结构课程设计- 复杂场景OCR识别

之前有人抄我的机器学习是吧，嘛算了无所谓爱咋咋地吧我开摆了

这个玩意没啥好说的

## 2023/5/4

基础功能已经实现，正在考虑增加R-ESRGAN算法以针对低分辨率图像增强

## 2023/5/5

尝试使用PPGAN，效果不好，换Real-ESRGAN尝试中

引入了Real-ESRGAN，但是好像会出现Attribute ERROR

## 2023/5/6

注意到REALSR算法，似乎有点用，试试看吧

RealSR还不错，但是只支持对1000*1000以下的文件进行超分，先凑活着用，但是由于其模型太大故不上传

## 2023/5/7

超分辨率这一块大概没啥问题了，计划重新改一下界面，首先是要把识别到的文字和最终图片一起输出