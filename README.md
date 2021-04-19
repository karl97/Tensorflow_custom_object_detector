# Tensorflow_custom_object_detector
Training, evaluation and conversions to TFLite of a custom object detection model from tensorflow object detection zoo.

1. Get a suitable model from the Object Detection zoo.
2. Use the training script to fine tune the model with your own custom data (TFRecord format).
3. Use the evaluation script simultaneously to evaluate the object detector at each checkpoint.
4. Choose the best checkpoint.
5. Convert the saved model to TFLite format for mobile inference.
