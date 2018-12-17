# Face-Detection-and-Tracking-Based-on-MTCNN-and-OpenTLD
I optimized OpenTLD making it run faster and better for face tracking.

This version of TLD below is faster and more stable than that in OpenCV. I deleted some funtions to make it run faster. What is more, use rnet to judge the face that TLD produced. In order to get a stable bounding box, I fix the width and height that MTCNN provides on the firt frame. The running speeds on my PC(Intel® Xeon(R) CPU E5-2673 v3 @ 2.40GHz × 48) using ncnn inferenc framework are about 30ms(MTCNN), 30ms(TLD init), 10ms(TLD tracking).

### Reference:
https://github.com/CongWeilin/mtcnn-caffe
https://github.com/alantrrs/OpenTLD
