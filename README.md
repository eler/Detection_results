# Detection_results

|阶段|实现平台|检测框架|模型|数据库|硬件|帧率|训练时间|mAP|准确率|召回率|
|----|----|----|----|----|----|----|----|----|----|----|
|训练|caffe|Ssd-300|mobileNet|voc0712|gtx1080|59|20h|0.727|		
										
|测试|caffe|Faster-rcnn|vgg|voc0712|cpu|1.0/13|\|\|
|测试|caffe|Faster-rcnn|zf|voc0712|cpu|1.0/3|\|\|	
|测试|caffe|Faster-rcnn|vgg|voc0712|gtx1080|5\|\	|
|测试|caffe|Faster-rcnn|zf|voc0712|gtx1080|17|\|\|	
										
|测试|tensorflow|Ssd-300|vgg|voc0712|gtx1080|46|\|\|			
							
|训练|caffe|Ssd-300|vgg|parking003|gtx1080ti|?|1.5h|0.92|		
	
