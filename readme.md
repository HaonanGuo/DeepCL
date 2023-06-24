# DeepCL: Deep Change Feature Learning on Remote Sensing Images in the Metric Space
The manuscript is in the peer review process and the training and evaluation code will be released once it is accepted~ <br/>
Coming Soon :)<br/>

Dataset
----
[1.WHU-CD](https://study.rsgis.whu.edu.cn/pages/download/building_dataset.html)<br/>
[2.LEVIR-CD](http://chenhao.in/LEVIR/)  <br/>
[3.Google Earth Dataset](https://github.com/GeoZcx/A-deeply-supervised-image-fusion-network-for-change-detection-in-remote-sensing-images/tree/master/dataset)  <br/>


The code
----
### Requirements
* torch
* torchvision
* pillow
* cv2

### Usage
Clone the repository:git clone https://github.com/HaonanGuo/DeepCL.git<br/>
->Run [s1_Make_Dataset.py](https://github.com/HaonanGuo/DeepCL-Efficient-Building-Footprint-Segmentation-Framework/blob/main/s1_Make_Dataset.py) <br/>
->Run [s2_Train_DeepCL.py](https://github.com/HaonanGuo/DeepCL-Efficient-Building-Footprint-Segmentation-Framework/blob/main/s2_Train_DeepCL.py) <br/>
->Run [s3_Test_DeepCL.py](https://github.com/HaonanGuo/DeepCL-Efficient-Building-Footprint-Segmentation-Framework/blob/main/s3_Test_DeepCL.py) <br/>

You can also download the trained model weights for evaluation:<br/>
| Dataset | LEVIR-CD     | WHU-CD     | GoogleDataset     |
| :--------: | :--------: | :--------: | :--------: |
|  DeepCL weights | Coming Soon |Coming Soon  | Coming Soon  |

Help
----
Any question? Please contact us with: haonan.guo@whu.edu.cn
