# HRC_WHU: High-Resolution Cloud Detection Validation Dataset

The high-resolution cloud detection validation dataset, termed HRC\_WHU, comprises 150 high-resolution images acquired with three RGB channels and a resolution varying from 0.5 to 15 meters across different global regions. As shown in Fig. 1, the images were collected from Google Earth in five main land-cover types, i.e., water, vegetation, urban, snow/ice, and barren. The associated reference cloud masks were digitized by experts specializing in remote sensing image interpretation from Wuhan University. The established high-resolution cloud cover validation dataset has been made available online.

![image](https://raw.githubusercontent.com/dr-lizhiwei/HRC_WHU-High-resolution-cloud-detection-datasetset/main/Preview-of-HRC_WHU.jpg)

Fig. 1. Preview of images in HRC\_WHU

In the procedure of delineating the cloud mask for high-resolution imagery, we first stretched the cloudy image to the appropriate contrast in Adobe Photoshop. The lasso tool and magic wand tool were then alternately used to mark the locations of the clouds in the image. The manually labeled reference mask was finally created by assigning the pixel values of cloud and clear sky to 255 and 0, respectively. Note that a tolerance of 5–30 was set when using the magic wand tool, and the lasso tool was used to modify the areas that could not be correctly selected by the magic wand tool. As we did in a previous study (Li et al., 2017), the thin clouds were labeled as cloud if they were visually identifiable and the underlying surface could not be seen clearly. Considering that cloud shadows in high-resolution images are rare and hard to accurately select, only clouds were labeled in the reference masks.

The full HRC_WHU dataset can be downloaded from [**Baidu Disk**](https://pan.baidu.com/s/1thOTKVO2iTAalFAjFI2_ZQ) (password: ihfb) or [**Google Drive**](https://drive.google.com/file/d/1qqikjaX7tkfOONsF5EtR4vl6J7sToA6p/view?usp=sharing). For any questions, contact <a href='https://zhiweili.net/'>Dr. Zhiwei Li</a> at <a href="mailto:dr.lizhiwei@gmail.com">dr.lizhiwei(AT)gmail.com</a>. This dataset is shared for academic purposes only. If you use the dataset, you should appropriately cite our paper:

**Li, Z., Shen, H., Cheng, Q., Liu, Y., You, S., & He, Z. (2019). Deep learning based cloud detection for medium and high resolution remote sensing images of different sensors. *ISPRS Journal of Photogrammetry and Remote Sensing*, vol. 150, pp. 197-212, 2019. ([PDF](http://sendimage.whu.edu.cn/en/wp-content/uploads/2019/03/2019_PHOTO_Zhiwei-Li_Deep-learning-based-cloud-detection-for-medium-and-high-resolution-remote-sensing-images-of-different-sensors.pdf))**

