

原理
==== 
    相似三角形：假设有一个宽度为 W 的目标或者物体，然后将这个目标放在距离相机为 D 的位置。
    用相机对物体进行拍照并且测量物体的像素宽度 P
    这样就得出了相机焦距的公式：
                                               F = (P x D) / W 
                          
    假设在相机距离D = 24 英寸的地方放一张标准的8.5 x 11 英寸的A4 纸（横着放；W = 11）并且拍下一张照片。
    测量出照片中 A4 纸的像素宽度为 P = 249 像素。
    因此焦距 F 是：
                                      F = (248px x 24in) / 11in = 543.45 
                    
    继续将相机移动靠近或者离远物体或者目标时，用相似三角形来计算出物体离 相机的距离： 
                                                D’ = (W x F) / P 
                            
    为了更具体，假设将相机移到距离目标 3 英尺的地方并且拍下上述的 A4 纸。 
    通过自动的图形处理可以获得图片中 A4 纸的像素距离为 170 像素。将这个代入公式得： 
                                      D’ = (11in x 543.45) / 170 = 35 英寸 
                    
 运行结果
 ====
   <img align="center" src="https://github.com/nonlau/distance-to-camera/blob/master/images/r1.png"/>
   <img align="center" src="https://github.com/nonlau/distance-to-camera/blob/master/images/r2.png"/>
 
 
