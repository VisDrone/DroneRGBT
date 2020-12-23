# DroneRGBT
RGB-T Crowd Counting from Drone: A Benchmark and MMCCN Network

## Abstract
Crowd counting aims to identify the number of objects and plays an important role in intelligent transportation, city management and security monitoring. The task of crowd counting is  much challenging  because of scale variations, illumination changes, occlusions and poor imaging conditions, especially in the nighttime and haze conditions.
In this paper, we present a drone based RGB-Thermal crowd counting dataset (DroneRGBT) that consists of 3600 pairs of images and covers different attributes, including height, illumination and density. To exploit the complementary information in both visible and thermal infrared modalities, we propose a multi-modal crowd counting network (MMCCN) with a multi-scale feature learning module, a modal alignment module and an adaptive fusion module. Experiments on DroneRGBT demonstrate the effectiveness of the proposed approach. 

![dataset](https://github.com/VisDrone/DroneRGBT/blob/main/dataset.jpg)

## Dataset






## Code
![pipeline](https://github.com/VisDrone/DroneRGBT/blob/main/pipeline.jpg)




## Reference
@InProceedings{Peng_2020_ACCV,  
    author    = {Peng, Tao and Li, Qing and Zhu, Pengfei},  
    title     = {RGB-T Crowd Counting from Drone: A Benchmark and MMCCN Network},  
    booktitle = {Proceedings of the Asian Conference on Computer Vision (ACCV)},  
    month     = {November},  
    year      = {2020}  
}
