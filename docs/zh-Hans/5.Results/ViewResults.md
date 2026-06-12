---
title: 查看成果
sidebar_position: 6
---
## 查看成果


点击查看成果，跳转至result成果所在文件夹。

![](../../img/cn-img/企业微信截图_20260604120832.png)

### 去畸变影像
.temp/undistort文件夹里存放的去畸变影像（需要提前在设置里开启保留去畸变影像）。

![](../../img/cn-img/企业微信截图_20260604121347.png)

### 2D成果

2D文件夹里存放所有的二维成果。

![](../../img/cn-img/企业微信截图_20260604121532.png)
-   dom_tiles：正射影像图切片成果。
-   dsm_tiles：数字表面模型切片成果。
-   geotiffs：正射影像图（DOM）、数字表面模型（DSM）等成果。
-   split_dom：正射影像图分幅成果（需打开分幅输出）。

### 3D成果

3D文件夹里存放所有的三维成果。

![](../../img/cn-img/企业微信截图_20260604121849.png)

-   model-b3dm：3dtiles格式的三维模型成果。
-   model-fbx：fbx格式的三维模型成果。
-   model-glb：glb格式的三维模型成果。
-   model-gs-ply：ply格式的高斯模型成果。
-   model-gs-sog：sog格式的高斯模型成果。
-   model-gs-sog-tile：sog tile格式的高斯模型成果。
-   model-obj：obj格式的三维模型成果。
-   model-osgb：osgb格式的三维模型成果。
-   model-ply：ply格式的三维模型成果。
-   model-skp：skp格式的三维模型成果。
-   point-las：las格式的点云成果。
-   point-osgb：osgb格式的点云成果。
-   point-ply：ply格式的点云成果。
-   point-pnts：pnts点云成果。

### 空三成果

AT文件夹存放空三成果文件，mvs为原始空三成果，mvs_undistort为去畸变空三成果。

![](../../img/cn-img/企业微信截图_20260604123031.png)

### 日志文件

logs文件夹存放工程日志文件。

>若重建失败，可将log日志发给技术支持，以便定位报错原因。

![](../../img/cn-img/企业微信截图_20260604123249.png)

### 缩略图

thumbnail文件夹存放任务缩略图。

![](../../img/cn-img/企业微信截图_20260604123613.png)

-   camera_1_residual：相机残差分布图。
-   overlap_map：重叠覆盖分布图。
-   rgb_thumbnail：![](../../img/cn-img/image138.png)存放至此，普通分辨率缩略图。 

-   rgb_thumbnail_4K：4K高清DOM缩略图。