# yolov5-csgo
这是一个根据教程写的csgo-ai和我自己训练的模型，还有数据集
教程来自：Caesar丶L url:https://space.bilibili.com/14796576
https://www.bilibili.com/video/BV1b64y1q7sC?spm_id_from=333.1007.top_right_bar_window_custom_collection.content.click
他讲得很好！
我的数据集：https://cvat.org/projects/24343?page=1服务器寄了我的数据没了（哭了）
现在数据集还是较小的，后面有时间会多添加些，大家也可以多添加、多标注些。一起用！
首先你得照着教程安装YOLOv5
将这三个文件移入![屏幕截图 2022-01-19 105916](https://user-images.githubusercontent.com/65958464/150060067-ed1d47e8-85d3-4cd7-acec-275563e7f761.jpg)
找到data文件夹![屏幕截图 2022-01-19 110005](https://user-images.githubusercontent.com/65958464/150060153-0e2be836-36bb-48c0-a178-6befce956cf6.jpg)
创建一个文件夹，我的是mydata!![屏幕截图 2022-01-19 110053](https://user-images.githubusercontent.com/65958464/150060186-1ffa712d-417c-4602-b585-3a6c3acd2865.jpg)
然后在里面创建这两个文件夹，![屏幕截图 2022-01-19 110144](https://user-images.githubusercontent.com/65958464/150060233-7cda4e5c-41d1-40cc-83f1-78e1a47ba704.jpg)必须的！images存图片，labels存标签
然后分别在两个文件夹下创建train，val 文件夹。![屏幕截图 2022-01-19 110221](https://user-images.githubusercontent.com/65958464/150060271-a9635f5d-371b-41c5-9310-b34763ef063e.jpg)
val文件的图片就在train里随便找几张就行，labels的val文件夹下同理，名字应对应!![屏幕截图 2022-01-19 112242](https://user-images.githubusercontent.com/65958464/150060319-5b5c27a0-20cd-4d37-ac5a-017601dd3774.jpg)
模型太大无法上传，自己训练吧！
mydata.yaml位置在：![屏幕截图 2022-01-19 114643](https://user-images.githubusercontent.com/65958464/150060408-64e2b5b0-67db-4ece-8581-de7bcbd8342f.jpg)
我的图片，标签在：https://cvat.org/projects/24343?page=1
点击这里导出数据集![屏幕截图 2022-01-19 120024](https://user-images.githubusercontent.com/65958464/150061630-611043bc-6c7c-4097-953c-37380ab6d9d9.jpg)
勾选这里下载标签和图片![屏幕截图 2022-01-19 115002](https://user-images.githubusercontent.com/65958464/150061634-777e8557-13f4-4e65-a5d0-723d77f20316.jpg)

