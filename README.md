# autoLabeling
自动标注工具

# 一、配置环境

	pytorch版本大于1.2即可。requirememts.txt是我的环境（windows）。如果你也是cuda10.1版本，可以使用如下命令：
	
	pip install torch==1.6.0+cu101 torchvision==0.7.0+cu101 -f https://download.pytorch.org/whl/torch_stable.html
	
# 二、配置参数及测试

	1.放置自己的权重；
	
	2.修改yoloMain.py读取文件的路径，及对应imgSize的大小（该值大小应和yolov3.cfg文件height&width的大小一样）；
	
	3.测试yoloMain.py是否正常；
	
# 三、自动标注数据

	设置相应的路径，运行dataLabeling.py；