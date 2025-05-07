# abhishek-raj-facenet
1.Face Verification with MTCNN and FaceNet — SageMaker-Trained, Locally Deployed

2.This project demonstrates a complete face verification pipeline where a FaceNet model was trained on AWS SageMaker and is now being used for local inference. The system uses MTCNN for detecting facial regions, and FaceNet to extract 128-dimensional embeddings from the cropped faces.

3.It compares two input images and evaluates whether they belong to the same individual using Euclidean distance between embeddings. The project is split into two key components:

a.face-training: Training logic built for SageMaker (includes model architecture, preprocessing, and export logic) b.cyfuture-inferencing: Lightweight script for running inference on saved models, detecting faces, generating embeddings, and visualizing comparisons

