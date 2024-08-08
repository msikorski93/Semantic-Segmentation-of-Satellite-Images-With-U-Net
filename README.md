# Semantic-Segmentation-of-Satellite-Images-With-U-Net
![ alt text ](https://img.shields.io/badge/license-MIT-green?style=&logo=)
![ alt text ](https://img.shields.io/badge/-Jupyter-F37626?logo=Jupyter&logoColor=white)
![ alt text ](https://img.shields.io/badge/-NumPy-013243?logo=Numpy&logoColor=white)
![ alt text ](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=TensorFlow&logoColor=white)
![ alt text ](https://img.shields.io/badge/-Keras-D00000?logo=Keras&logoColor=white)

This notebook was developed to perform a semantic segmentation problem on satellite urban imagery of Dubai. An artificial neural network with U-Net architecture was built to complete this task. The learning process was monitored and evaluated with common image segmentation metrics: Jaccard index (IoU) and Dice index. The visual assessment of predicted and ground truth masks demonstrate fairly high accuracy and performance. The U-Net proved to serve as a foundational framework and to be highly effective in handling large-scale image datasets. The custom loss function, which was a combination of Dice loss and Focal loss, contributed to the model's robustness and accuracy, ensuring precise segmentation across multiple classes. The success of this project highlights the reliability of deep learning in land cover classification and segmentation.

<p align='left'>
<img src='https://github.com/user-attachments/assets/a262f2cf-ef80-4971-bd27-b607b161775d' height='200'/>
<p align='left'>
<img src='https://github.com/user-attachments/assets/72a99199-af78-4586-8daa-6d385773ddb3' height='200'/>
<p align='left'>
<img src='https://github.com/user-attachments/assets/8a9487e1-9ae0-4a7e-b14a-d43c9dff4fc4' height='200'/>
<p align='left'>
<img src='https://github.com/user-attachments/assets/aa6b90ed-01b8-433d-9767-725c33c9adbf' height='200'/>
</p>
Achieved evaluation scores:

**IoU:** 0.619995<br>
**Dice:** 0.765428<br>
**Accuracy:** 0.863537
