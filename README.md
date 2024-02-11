# YoloV3
End-to-end custom implementation of YOLOv3 (You Only Look Once version 3) using Keras3 for personal practice and deepening understanding in computer vision. 
This project is my exploration into the intricacies of real-time object detection, leveraging YOLOv3's robust architecture with the flexibility and power of Keras3.

## Instruction
To run the YOLOv3_SelfAttention.ipynb notebook in Google Colab, first ensure you've selected a GPU runtime via "Runtime" > "Change runtime type" > "GPU". 
The notebook, pre-configured with hyperparameters, utilizes the VOC 2007 dataset.
Sequentially execute code cells from the start, omitting those under "Sanity Check". 
Dependencies will install as needed. 
For additional guidance, consult the notebook's embedded comments.

## Features and Enhancements
This project explores enhancing a YOLOv3 model using Keras3, notable for its backend-agnostic feature, allowing flexibility across different backend frameworks. A key experiment was integrating a self-attention layer to potentially improve object size detection, aiming to achieve this without significantly increasing the model's complexity. While the effectiveness of this enhancement hasn't been fully tested, and visualizations of the attention mechanism were not developed, the project serves me as a valuable learning exercise. Furthermore, I dedicated effort to developing custom functions for the project, prioritizing the optimization of these functions through vectorized operations. This approach was intended to enhance computational efficiency, a critical factor in the performance of deep learning models.
Additionally, the project utilizes ResNet50 as the backbone, pretrained on ImageNet, to leverage its powerful feature extraction capabilities, although exploring alternative architectures could yield different insights.

## Results
<div style="display: flex;">
  <img src="https://github.com/MosheDorZarka/YoloV3/blob/main/results/result_1.png" alt="YOLO Custom Model Results" width="300" height="300">
  <img src="https://github.com/MosheDorZarka/YoloV3/blob/main/results/result_2.png" alt="YOLO Custom Model Results" width="300" height="300">
</div>
