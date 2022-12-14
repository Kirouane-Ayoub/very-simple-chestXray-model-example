# CheXNet: Radiologist-Level Pneumonia Detection on Chest X-Rays with Deep Learning

We develop an algorithm that can detect pneumonia from chest X-rays at a level exceeding practicing radiologists. Our algorithm, CheXNet, is a 121-layer convolutional neural network trained on ChestX-ray14, currently the largest publicly available chest X-ray dataset, containing over 100,000 frontal-view X-ray images with 14 diseases. Four practicing academic radiologists annotate a test set, on which we compare the performance of CheXNet to that of radiologists. We find that CheXNet exceeds average radiologist performance on the F1 metric. We extend CheXNet to detect all 14 diseases in ChestX-ray14 and achieve state of the art results on all 14 diseases.

U can read the paper : https://arxiv.org/abs/1711.05225


![41597_2021_863_Fig17_HTML](https://user-images.githubusercontent.com/99510125/192345460-ff3d13d3-9604-488f-9165-ae48f52014d7.png)

# about dataset : 
ChestX-ray14 is a medical imaging dataset which comprises 112,120 frontal-view X-ray images of 30,805 (collected from the year of 1992 to 2015) unique patients with the text-mined fourteen common disease labels, mined from the text radiological reports via NLP techniques. It expands on ChestX-ray8 by adding six additional thorax diseases: Edema, Emphysema, Fibrosis, Pleural Thickening and Hernia.

U can know more about ChestX-ray14 dataset : https://paperswithcode.com/dataset/chestx-ray14
