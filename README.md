# German Traffic Sign CNN Classification Model

This project aims to accurately classify German traffic signs using machine learning techniques. The dataset used is The German Traffic Sign Benchmark, a multi-class, single-image classification problem with over 40 different classes and contains more than 50,000 images in .ppm format.

## Dataset

The dataset used in this project is hosted on Google Drive due to its size. You can access it using the following link: https://drive.google.com/drive/folders/19C7n9xnCATdXXjd2VsD8OmK1l2BphwAi?usp=sharing

## Features

- Utilized EDA and feature engineering to preprocess the dataset.
- Employed Keras Tuner to identify the best model architecture.
- Achieved a training accuracy of 99% and a validation accuracy of 98%.
- Utilized Softmax activation function with Adam optimizer (learning rate = 0.0001).
- Chose sparse categorical cross-entropy as the loss function.
- Utilized an image size of (50, 50, 3) and implemented 3 convolutional layers with kernel size 5 and filters of 48, 80, and 48 respectively.
- Employed a flattening layer and a dense layer for classification.
- Successfully evaluated the model on test images, achieving over 98% confidence in predictions.

## Project Files

The project is contained in a Jupyter Notebook **GSTRB Notebook.ipynb**.
The trained model is available as a **gstrb_models.h5** file

## Usage
1. Open the Jupyter Notebook file (GSTRB Notebook.ipynb) to view the project.
2. Navigate to the project notebook and open it using Jupyter Notebook or Jupyter Lab.
3. Change the input directory for images as per requirement.
4. Modify the file paths for image input in the notebook based on your specific directory structure or requirements.
5. Install the necessary dependencies using code: pip install -r requirements.txt
6. Load the trained model, use the gstrb_models.h5
    **from tensorflow.keras.models import load_model
    model = load_model('gstrb_models.h5')**

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or further information regarding this project, please contact **sanchitsingla1403@gmail.com**
---

