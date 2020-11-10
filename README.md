# semantic_loc--real-time-instance-segmentation-in-trt4-in-TX2

## PERFORMANCE
The instance-segmentation network(based on Mask RCNN) ran on TX2 with TensorRT fp16 mode, can achieve 24ms/frame, 42ms/2 frames. 
I also have a tensorflow C++ / cpu version both on x86 and arm, the speed is slower than the TensorRT version, about 70ms/frame, 115ms/2frames.

## required
After test, the only worked software version for my MaskRCNN_Trt is:
tf-gpu==1.12.0 ,keras==2.1.6, tensorrt4.0.1.6, uff0.4
the software for my Mask_RCNN_cpu is:
tf==1.10.0, keras==2.1.6/2.2.4?

## reslut 0
<p align="center">
<img src="https://github.com/hwh-hit/semantic_loc--real-time-instance-segmentation-in-trt4-in-TX2-/raw/main/results/r0.png">
</p>

## reslut 1
<p align="center">
<img src="https://github.com/hwh-hit/semantic_loc--real-time-instance-segmentation-in-trt4-in-TX2-/raw/main/results/r1.png">
</p>

## reslut 2
<p align="center">
<img src="https://github.com/hwh-hit/semantic_loc--real-time-instance-segmentation-in-trt4-in-TX2-/raw/main/results/r2.png">
</p>
