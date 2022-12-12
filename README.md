# HW2_Bezier_Spline_Modeling

SJTU-SE3306 计算机图形学 第2次作业

任务划分为三个部分，分别是

* 输入控制顶点，绘制多条Bézier曲线；

* 旋转绘制Bézier曲线，预览旋转体模型；

* 生成网格模型，根据距离改变细分程度，并将模型转化为OBJ格式便于保存和读取。

程序操作说明

* 输入控制顶点前需通过ImGui界面设定贝塞尔曲线的细分采样率，然后鼠标点击输入三次贝塞尔曲线的四个控制顶点，完成后即可看到添加曲线的按钮。添加后续曲线时可选择重新设定采样率，也可以设定曲线的连续性。完成输入后按ESC即可保存进入下一步

* 在第二部分中可以预览旋转生成的一族曲线，可以通过WASD和鼠标控制相机运动，按ESC将曲线数据保存为txt并进入下一部分

* 进入第三部分时，将根据曲线数据生成网格模型。该部分默认通过鼠标和键盘控制相机运动，默认自动根据视点物体距离进行LOD。可以通过左ALT键唤出鼠标，从而与ImGui界面交互，比如手动修改细分采样率和切换线框模式；也可以通过右ALT键重新用鼠标控制相机。最后按ESC键可退出，并将模型保存为OBJ文件
