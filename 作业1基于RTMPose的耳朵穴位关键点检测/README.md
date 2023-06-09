# OpenMMLabCamp-MAMBO
Warehouse for submitting tasks in OpenMMLabCamp

题目：基于RTMPose的耳朵穴位关键点检测

背景：根据中医的“倒置胎儿”学说，耳朵的穴位反映了人体全身脏器的健康，耳穴按摩可以缓解失眠多梦、内分泌失调等疾病。耳朵面积较小，但穴位密集，涉及耳舟、耳轮、三角窝、耳甲艇、对耳轮等三维轮廓，普通人难以精准定位耳朵穴位。

任务
1.Labelme标注关键点检测数据集（子豪兄已经帮你完成了）
2.划分训练集和测试集（子豪兄已经帮你完成了）
3.Labelme标注转MS COCO格式（子豪兄已经帮你完成了）
4.使用MMDetection算法库，训练RTMDet耳朵目标检测算法，提交测试集评估指标
5.使用MMPose算法库，训练RTMPose耳朵关键点检测算法，提交测试集评估指标
6.用自己耳朵的图像预测，将预测结果发到群里
7.用自己耳朵的视频预测，将预测结果发到群里
需提交的测试集评估指标（不能低于baseline指标的50%）

mmdet结果：

![image](https://github.com/MAMOB/OpenMMLabCamp-MAMBO/assets/42363751/301f6ac4-8837-42bb-bd4c-814d4a9ee0a0)

mmpose结果：

![image](https://github.com/MAMOB/OpenMMLabCamp-MAMBO/assets/42363751/e99c58bb-df87-44cb-807d-8c7537813862)

可视化图：

![image](https://github.com/MAMOB/OpenMMLabCamp-MAMBO/assets/42363751/2eb6cc0a-3495-4c5c-876a-bed015dffc71)

