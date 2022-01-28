# W.O.W-Attachment-2022
This project, titled "Performing Daily Tasks with a Robot Arm", uses the Universal Robot Arm to carry out tasks, such as sorting items, folding clothes, etc. This algorithm requires computer vision and image classification models using OpenCV and Pytorch libraries, in order to identify objects and navigate obstacles. The robot arm is controlled by assigning paths using the URX library.

To train an image classification model using Pytorch, use final_train_model_recyclables.ipynb and change the necessary paths & number of classes/epochs accordingly. This code also allows for evaluation of the model after training.

To train an image classification model using Tensorflow (which was not used for this project), use train_model.ipynb and change the necessary paths. After training, download the checkpoint files to be used in object detection.
