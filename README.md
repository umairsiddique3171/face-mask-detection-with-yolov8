# face-mask-detection-with-yolov8

This project develops a robust system for detecting face masks using a custom-trained YOLOv8 model. The YOLOv8 object detection architecture, trained on a custom dataset, enables efficient detection of whether individuals are wearing face masks from video footage.

https://github.com/umairsiddique3171/face-mask-detection-with-yolov8/assets/148565997/d26b0704-8b1e-4bd6-a78b-f9f0881c8ec1

## Project Structure

- **Dataset Collection and Preprocessing**: Images of individuals with and without face masks are collected and preprocessed to train the YOLOv8 model.
- **Training YOLOv8**: The model is trained on the processed images to accurately detect face masks.
- **Model Evaluation**: The model's effectiveness is evaluated using metrics like precision, recall, and mAP.
- **Deployment**: The trained model is deployed to detect face masks in real-time video feeds.

## Dataset

The dataset includes images with annotated bounding boxes indicating the presence of face masks. The dataset can be found [here](https://www.kaggle.com/datasets/aditya276/face-mask-dataset-yolo-format).

## Training

The YOLOv8 model is trained using the custom dataset with the goal of minimizing detection loss and enhancing accuracy in face mask detection. Training details include:
- **Epochs**: 15
- **Batch Size**: 30

## Model Evaluation

The model's performance is evaluated on a set of validation images. Key metrics include:
- **Precision**: 0.942 
- **Recall**: 0.784
- **mAP**: 0.836         

## Sample Video Detection

The trained model is utilized to detect face masks in sample footage. The results can be downloaded and viewed [here](https://github.com/umairsiddique3171/face-mask-detection-with-yolov8/blob/main/results.mp4).

## Conclusion

This project demonstrates the effectiveness of custom-trained YOLOv8 models for face mask detection, offering a reliable solution for enhancing public health measures.

## License

This project is licensed under the [MIT License](https://github.com/umairsiddique3171/face-mask-detection-with-yolov8/blob/main/LICENSE).

## Author

[@umairsiddique3171](https://github.com/umairsiddique3171)
