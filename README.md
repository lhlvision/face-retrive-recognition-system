# face-retrive-system
亚洲人脸检索识别模型，支持人脸识别，人脸检索，支持各种平台，总模型大小9MB，i7、android  cpu运行40ms，库独立，完全没有第三方库，方便部署
face recognition system face retrive system. android,ios , linux ,windows, mac and so on.model size is 9MB,very fast  
人脸检测20ms 关键点5ms  人脸特征20ms，由于主要是针对移动端人脸进行离线识别，所以检测的性能在大场景情况下稍微有点弱，  
如果需要大场景需要更新检测模型库，后期逐步开发模型库


******face model db nums is 5*******  
*********begin retrive**************  
detect time is : 20.75 face nums is: 5  
**********0*************  feats extract time is 19.34  face box is :1.0000 58.6 433.3 205.9 628.2  
facedb id is 0->1.000000  
facedb id is 1->0.074172  
facedb id is 2->0.037534  
facedb id is 3->0.102323  
facedb id is 4->-0.018581  
**********1*************  feats extract time is 20.80  face box is :1.0000 655.8 76.2 814.6 275.5  
facedb id is 0->0.074172  
facedb id is 1->1.000000  
facedb id is 2->-0.058865  
facedb id is 3->-0.012305  
facedb id is 4->-0.047254  
**********2*************  feats extract time is 24.11  face box is :0.9999 46.4 103.0 225.1 308.1  
facedb id is 0->0.037534  
facedb id is 1->-0.058865  
facedb id is 2->1.000000  
facedb id is 3->0.018783  
facedb id is 4->-0.135428  
**********3*************  feats extract time is 22.78  face box is :0.9999 663.1 466.6 811.4 655.8  
facedb id is 0->0.102323  
facedb id is 1->-0.012305  
facedb id is 2->0.018783  
facedb id is 3->1.000000  
facedb id is 4->0.073781  
**********4*************  feats extract time is 18.26  face box is :0.9996 374.3 94.5 536.9 326.6  
facedb id is 0->-0.018581  
facedb id is 1->-0.047254  
facedb id is 2->-0.135428  
facedb id is 3->0.073781  
facedb id is 4->1.000000



qq交流群 1076120833

./faceretrive image.jpg image.jpg   
执行后该目录会在当前目录保存测试图像的人脸id，以判断是否正确
