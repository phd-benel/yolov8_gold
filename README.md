# yolov8_gold

Hy, Peace be upon you, 
This is the source code for the paper, "Detecting Broken Glass Insulators for Automated UAV Power Line Inspection Based on an Improved YOLOv8 Model".

## Paper Abstract

Intelligent drone inspection of power lines using computer vision techniques is a very promising research topic. In particular, the detection of broken glass insulators due to their essential role in the proper functioning of electrical transmission lines. However, detection of such defects is challenging due to their small size coupled with complex aerial image backgrounds and limited dataset availability. In this regard, this paper uses advanced object detection algorithms to achieve real-time monitoring of broken glass insulators using drones by offering main contributions on two aspects. First, a large-scale aerial image dataset from Vietnam was meticulously constructed, including 1,010 labeled original images. It serves as a valuable resource for those engaged in the automation of power line inspections. Second, an improved Yolov8 detection model is introduced, involving the substitution of the Yolov8’s neck with that of Gold-Yolo. This modification optimizes the model by incorporating an innovative gather-and-distribute mechanism, particularly beneficial for improving the detection of anomalies within complex scenarios. Experimental results demonstrate that model surpasses equivalent-scale models, such as Yolov8-m, Yolov7, and Yolov6-v3.0-m, exhibiting notable improvements. The model shows improvements of up to 2,1% in mean Average Precision mAP:50 (reaching a maximum of 94,1% in mAP:50) while maintaining resource efficiency, with a smaller model size of at least 17.31% compared to other models, and it exhibits real-time performance capabilities. 

### Usage

Run this colab book to reproduce the results

### Data

Data used for the study can be found here : 

## Citation

Too add

## License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). Please see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

We express our gratitude to Ultralytics YOLOv8 and the contributors of the objectdetection_script repository for their valuable contributions and resources, which greatly assisted in the development and execution of this research.
