# CSE541-Computer-Vision-2022-COTS
Object Detection using YOLOv5 

<img align= "center" width="589" alt="yolo" src="https://user-images.githubusercontent.com/61927685/165143930-e8d95cab-21dc-42b3-8411-7509fcf3f8b1.png">

The outbreak of COTS i.e. Crown Of Thrones Starfish causes great harm to the coral reef of the surrounding region. One such scenario took place at Great Barrier Reef,
Australia. In order to protect the aquatic life from COTS which
eats up the faster growing corals and significantly damages the
reef and to make sure of the sustained development of Barrier
Reef, we should have a keen check over the population of ‘COTS’
in the entire region. Manual processes can be futile in marine life
over a large area. The problem can be solved by using Objection
Detection a key aspect of Computer Vision. Contributing to the
fact in such case we need more precision in terms of timely
detection than in terms of accuracy.
Referring to the current
state-of-art models for real time we tried implementing the novel
Yolov5 model both small and medium but the results in terms
of medium were quite remarkable, Yolov5 is the most powerful
objection detection algorithm at present, to better apply it in
the actual environment, especially in the supervision of COTS.


F1 Vs Confidence          |  Precision Vs Confidence
:-------------------------:|:-------------------------:
![f1c](https://user-images.githubusercontent.com/61927685/165143374-903ee3ef-a33b-4df7-901a-419ecb736931.png) | ![pc](https://user-images.githubusercontent.com/61927685/165143738-05126fd9-22b4-4a6b-8f3d-99dd655c9812.png)

Recall Vs Confidence          |  Precision Vs Recall
:-------------------------:|:-------------------------:
![rc](https://user-images.githubusercontent.com/61927685/165143795-920ae22b-d3e9-4766-bf34-557661903da8.png) | ![pr](https://user-images.githubusercontent.com/61927685/165143831-c949d2f9-a3ae-4496-9796-6c0de15781b7.png)

Matrices         |  Confusion Matrix
:-------------------------:|:-------------------------:
![matrix](https://user-images.githubusercontent.com/61927685/165143813-b388abef-4a8a-4b36-b36b-06b53cddec41.png) | ![Conf](https://user-images.githubusercontent.com/61927685/165143846-73e2a164-7767-41b4-b673-8b4bfff907e4.png)

Result:


<img width="667" alt="train" src="https://user-images.githubusercontent.com/61927685/165143895-2328fe4d-c919-41ee-941c-c7a139e89f3f.png">

How to execute:

[1] Download data from given link: https://www.kaggle.com/competitions/tensorflow-great-barrier-reef/data

[2] Download the ultralytics library from: https://github.com/ultralytics/yolov5

[3] Create an account in MLOps platform - Weight and Basis: https://wandb.ai/

[4] Upload both on google drive folder named as Tensorflow-Great-Barrier-Reef.

[5] Execute the ipynb file provided.

References:


[1] J. Liu, B. Kusy, R. Marchant, B. Do, T. Merz, J. Crosswell, A. Steven, N. Heaney, K. von Richter, L. Tychsen-Smith et al., “The csiro crown-of-thorn starfish detection dataset,” arXiv preprint arXiv:2111.14311, 2021.


[2] W. Wu, H. Liu, L. Li, Y. Long, X. Wang, Z. Wang, J. Li, and Y. Chang, “Application of local fully convolutional neural network combined with
yolo v5 algorithm in small target detection of remote sensing image,” PloS one, vol. 16, no. 10, p. e0259283, 2021.


[3] B. Yan, P. Fan, X. Lei, Z. Liu, and F. Yang, “A real-time apple targets detection method for picking robot based on improved yolov5,” Remote
Sensing, vol. 13, no. 9, p. 1619, 2021.


[4] G. Yang, W. Feng, J. Jin, Q. Lei, X. Li, G. Gui, and W. Wang, “Face mask recognition system with yolov5 based on image recognition,” in 2020
IEEE 6th International Conference on Computer and Communications (ICCC). IEEE, 2020, pp. 1398–1404.


[5] U. Nepal and H. Eslamiat, “Comparing yolov3, yolov4 and yolov5 for autonomous landing spot detection in faulty uavs,” Sensors, vol. 22, no. 2,
p. 464, 2022.


[6] Y. Fang, X. Guo, K. Chen, Z. Zhou, and Q. Ye, “Accurate and automated detection of surface knots on sawn timbers using yolo-v5 model.”
BioResources, vol. 16, no. 3, 2021
