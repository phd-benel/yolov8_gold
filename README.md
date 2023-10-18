# Yolov8_gold

Hy, Peace be upon you, 

This is the source code for the paper, "Detecting Broken Glass Insulators for Automated UAV Power Line Inspection Based on an Improved YOLOv8 Model" submitted in AI2SD Global Submit Symposium Serie On Energy, Enviromnent and Agriculture 15-17 NOVEMBER 2023 - MARRAKECH, MOROCCO

### Paper Abstract

Intelligent drone inspection of power lines using computer vision techniques is a very promising research topic. In particular, the detection of broken glass insulators due to their essential role in the proper functioning of electrical transmission lines. However, detection of such defects is challenging due to their small size coupled with complex aerial image backgrounds and limited dataset availability. In this regard, this paper uses advanced object detection algorithms to achieve real-time monitoring of broken glass insulators using drones by offering main contributions on two aspects. First, a large-scale aerial image dataset from Vietnam was meticulously constructed, including 1,010 labeled original images. It serves as a valuable resource for those engaged in the automation of power line inspections. Second, an improved Yolov8 detection model is introduced, involving the substitution of the Yolov8’s neck with that of Gold-Yolo. This modification optimizes the model by incorporating an innovative gather-and-distribute mechanism, particularly beneficial for improving the detection of anomalies within complex scenarios. Experimental results demonstrate that model surpasses equivalent-scale models, such as Yolov8-m, Yolov7, and Yolov6-v3.0-m, exhibiting notable improvements. The model shows improvements of up to 2,1% in mean Average Precision mAP:50 (reaching a maximum of 94,1% in mAP:50) while maintaining resource efficiency, with a smaller model size of at least 17.31% compared to other models, and it exhibits real-time performance capabilities. 

### Data

Data used for this study can be found here : https://github.com/phd-benel/VPMBGI 

### Model Architecture

Refer to this file for the model architecture : https://github.com/phd-benel/yolov8_improved_exp/blob/main/ultralytics/cfg/models/v8/yolov8_gold.yaml

![image](https://github.com/phd-benel/yolov8_gold/assets/82882383/28daae33-28c2-4113-abfc-cdf9e1a3a4a0)
Fig. 1. The overall simplified structure of the proposed improved model Yolov8-Gold. The orange blocks represent the new modules introduced in the Yolov8 architecture.

### Experiments

Run this Colab notebook to replicate the results obtained through the training of YOLOv8_Gold Model: https://colab.research.google.com/drive/1tuk6NXmcILxMYUiBYCgUQGLd_rMjtCWk?usp=sharing

### Results

Training results of Yolov8_gold_m' : ![results](https://github.com/phd-benel/yolov8_gold/assets/82882383/ab3fd48d-6be6-4121-b7fb-29cbe0afc82d)

Model weight of Yolov8_gold_m pretrained on VPMBGI : https://github.com/phd-benel/yolov8_gold/releases/download/untagged-afd4d8c9da44572fe2df/yolov8gold_m.pt

### Citation

Too add

### License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). Please see the [LICENSE.md](LICENSE) file for details.

### Acknowledgments

We express our gratitude to Ultralytics YOLOv8 and the contributors of the objectdetection_script repository for their valuable contributions and resources, which greatly assisted in the development and execution of this research.

### Contact 
Please don't hesitate to report an issue on this GitHub repository if you require further information or assistance. I would be delighted to provide help and support.
