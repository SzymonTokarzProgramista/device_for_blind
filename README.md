# device_for_blind
This device is designed to assist visually impaired individuals by recognizing printed characters and converting them into accessible formats (e.g., audio feedback). The system uses a camera to capture text in the environment, then processes the image using two machine learning models for character recognition.

The first model is a custom Convolutional Neural Network (CNN) trained from scratch for basic character classification. The second model leverages ResNet50 with transfer learning, allowing for more accurate and robust recognition, especially in more complex or noisy environments.

By combining these two models, the device ensures both speed and high accuracy in real-time character detection. It is intended to support independence for visually impaired users by helping them interpret written information in their daily lives.
