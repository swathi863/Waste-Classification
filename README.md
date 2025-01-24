# Waste-Classification
To develop a CNN model for classifying images of plastic waste, you'll follow a series of steps, including data collection, model architecture design, training, and evaluation.For the Data Collection step, the goal is to gather and prepare a dataset of images for your CNN model

   <h2> Data Collection </h2>
To develop an accurate CNN model, collecting a diverse dataset of images of plastic waste is crucial. The dataset should include various types of plastics, such as:

- Plastic bottles
- Plastic bags
- Plastic straws
- Other types of plastic waste

Ensure the dataset is diverse in terms of:

- Image resolution: Collect images with varying resolutions to simulate real-world scenarios.
- Lighting conditions: Include images taken in different lighting conditions, such as natural light, indoor lighting, and low-light environments.
- Angles: Collect images from various angles to capture different perspectives.
- Backgrounds: Include images with diverse backgrounds, such as outdoor environments, indoor settings, and cluttered spaces.

Label each image with its corresponding class, such as:

- Plastic bottle
- Plastic bag
- Plastic straw
- Other types of plastic waste

    <h2>  Data Preprocessing </h2>
Preprocess the collected dataset to prepare it for model training:

1. Resize images: Uniformly resize images to 224x224 pixels to ensure consistency.
2. Normalize pixel values: Scale pixel values to the range [0, 1] to improve model performance.
3. Apply data augmentation: Increase dataset diversity by applying the following techniques:

- Rotation: Rotate images by random angles to simulate different orientations.
- Flipping: Flip images horizontally and vertically to capture different perspectives.
- Color jittering: Randomly adjust image brightness, contrast, and saturation to simulate varying lighting conditions.
- Random cropping: Crop images randomly to capture different regions of interest.

These preprocessing steps will help ensure that the dataset is diverse, consistent, and ready for model training.
