# 📊 CIFAR-10 Classification Report

## 🧾 Overview

This assignment involves implementing and evaluating a series of deep learning models: **ANN, CNN, LeNet, AlexNet, VGG16, VGG19, ResNet50, and ResNet150**.  
These models were trained and tested on the **CIFAR-10** dataset to compare their performance in terms of classification accuracy, precision, recall, and F1-score.  

The report includes training-validation plots, confusion matrices, ROC curves, and a final comparison table.

---

## 📋 Model Comparison Table

| Model       | Parameters | Accuracy | Precision | Recall | F1 Score |
|-------------|------------|----------|-----------|--------|----------|
| ANN         | ...        | ...%     | ...       | ...    | ...      |
| CNN         | ...        | 52.65%     | 0.5846       | 0.5265    | 0.5054      |
| LeNet       | ...        | ...%     | ...       | ...    | ...      |
| AlexNet     | ...        | ...%     | ...       | ...    | ...      |
| VGG16       | ...        | 83.99%     | 0.8538       | 0.8399    | 0.8431      |
| VGG19       | ...        | ...%     | ...       | ...    | ...      |
| ResNet50    | ...        | 94.07%     | 0.9411       | 0.9407    | 0.9408      |
| ResNet150   | ...        | ...%     | ...       | ...    | ...      |

> ℹ️ *Fill in actual values after model training.*

---

## 🧠 Model-wise Evaluation

### ANN

<table>
<tr>
<td><img src="images/ann_conf_matrix.png" alt="ANN Confusion Matrix" width="400"/></td>
<td><img src="images/ann_roc.png" alt="ANN ROC Curve" width="400"/></td>
</tr>
<tr>
<td align="center"><b>Confusion Matrix</b></td>
<td align="center"><b>ROC Curve</b></td>
</tr>
</table>

---

### CNN

<table>
<tr>
<td><img src="images/cnn_conf_matrix.png" alt="CNN Confusion Matrix" width="400"/></td>
<td><img src="images/cnn_roc.png" alt="CNN ROC Curve" width="400"/></td>
</tr>
<tr>
<td align="center"><b>Confusion Matrix</b></td>
<td align="center"><b>ROC Curve</b></td>
</tr>
</table>

---

### LeNet

<table>
<tr>
<td><img src="images/lenet_conf_matrix.png" alt="LeNet Confusion Matrix" width="400"/></td>
<td><img src="images/lenet_roc.png" alt="LeNet ROC Curve" width="400"/></td>
</tr>
<tr>
<td align="center"><b>Confusion Matrix</b></td>
<td align="center"><b>ROC Curve</b></td>
</tr>
</table>

---

### AlexNet

<table>
<tr>
<td><img src="images/alexnet_conf_matrix.png" alt="AlexNet Confusion Matrix" width="400"/></td>
<td><img src="images/alexnet_roc.png" alt="AlexNet ROC Curve" width="400"/></td>
</tr>
<tr>
<td align="center"><b>Confusion Matrix</b></td>
<td align="center"><b>ROC Curve</b></td>
</tr>
</table>

---

### VGG16

<table>
<tr>
<td><img src="images/vgg16_conf_matrix.png" alt="VGG16 Confusion Matrix" width="400"/></td>
<td><img src="images/vgg16_roc.png" alt="VGG16 ROC Curve" width="400"/></td>
</tr>
<tr>
<td align="center"><b>Confusion Matrix</b></td>
<td align="center"><b>ROC Curve</b></td>
</tr>
</table>

---

### VGG19

<table>
<tr>
<td><img src="images/vgg19_conf_matrix.png" alt="VGG19 Confusion Matrix" width="400"/></td>
<td><img src="images/vgg19_roc.png" alt="VGG19 ROC Curve" width="400"/></td>
</tr>
<tr>
<td align="center"><b>Confusion Matrix</b></td>
<td align="center"><b>ROC Curve</b></td>
</tr>
</table>

---

### ResNet50

<table>
<tr>
<td><img src="images/resnet50_conf_matrix.png" alt="ResNet50 Confusion Matrix" width="400"/></td>
<td><img src="images/resnet50_roc.png" alt="ResNet50 ROC Curve" width="400"/></td>
</tr>
<tr>
<td align="center"><b>Confusion Matrix</b></td>
<td align="center"><b>ROC Curve</b></td>
</tr>
</table>

---

### ResNet150

<table>
<tr>
<td><img src="images/resnet150_conf_matrix.png" alt="ResNet150 Confusion Matrix" width="400"/></td>
<td><img src="images/resnet150_roc.png" alt="ResNet150 ROC Curve" width="400"/></td>
</tr>
<tr>
<td align="center"><b>Confusion Matrix</b></td>
<td align="center"><b>ROC Curve</b></td>
</tr>
</table>

---

## 📉 Training vs. Validation Loss Curves

| Model       | Loss Curve |
|-------------|------------|
| ANN         | ![](images/ann_loss_curve.png) |
| CNN         | ![](images/cnn_loss_curve.png) |
| LeNet       | ![](images/lenet_loss_curve.png) |
| AlexNet     | ![](images/alexnet_loss_curve.png) |
| VGG16       | ![](images/vgg16_loss_curve.png) |
| VGG19       | ![](images/vgg19_loss_curve.png) |
| ResNet50    | ![](images/resnet50_loss_curve.png) |
| ResNet150   | ![](images/resnet150_loss_curve.png) |

> 🧠 These plots help understand convergence behavior and overfitting across different model architectures.

