# SkinCancer-Detection
You can check this project on this below website ...

https://skin-cancer-detection-yn02.onrender.com


This Python script facilitates the diagnosis of skin lesions through a Convolutional Neural Network (CNN) model trained on dermatological images. Leveraging the capabilities of TensorFlow and Keras, the script loads a pre-trained CNN model (HAM10000_100epochs.h5) to predict the diagnosis of skin lesions based on user-provided images. The model categorizes lesions into seven classes, including Actinic keratoses, Basal cell carcinoma, Benign keratosis-like lesions, Dermatofibroma, Melanoma, Melanocytic nevi, and Vascular lesions.

The script utilizes the scikit-learn library for label encoding, mapping numerical values to corresponding lesion classes. The user can call the getPrediction function by providing the filename of the skin lesion image. The function resizes the image, scales pixel values, and feeds it into the pre-trained CNN model for prediction. The diagnosis is then returned, indicating the most likely skin lesion class.

The inclusion of an example image (example.jpg) demonstrates the functionality of the script. Users can integrate this code into applications or systems for automated skin lesion diagnosis, aiding in early detection and medical decision-making.

