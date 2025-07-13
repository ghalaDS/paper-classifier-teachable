# paper-classifier-teachable
This project classifies different types of paper using a Teachable Machine image model. The model identifies whether the uploaded image is **Lined, Grid, Dotted, or Plain** paper. It's deployed and tested in Google Colab using TensorFlow and Keras.

---

## Example Output

<img src="./Screenshot%202025-07-12%20150128.png" width="300"/>

---

## Files

- `keras_model.h5` — Pre-trained model from Teachable Machine  
- `labels.txt` — Class labels used by the model  
- `my_image.jpg` — Sample image used for testing  
- `classifier.ipynb` — Jupyter Notebook to run the model in Google Colab  

---

## How to Use (in Google Colab)

1. Open the `classifier.ipynb` notebook in Google Colab.
2. Upload the following files into the Colab session:
   - `keras_model.h5`
   - `labels.txt`
   - `your_image.jpg` (or any image you want to classify)
3. Install the required packages by running:
   ```python
   !pip install tensorflow==2.12.1 pillow
4.Run the notebook cells in order to:
-Load the model

-Load and preprocess the image

-Make a prediction

-Display the result


## Supported Classes
-Lined Paper

-Grid Paper

-Dotted Paper

-Plain Paper


## Built With
-Teachable Machine by Google

-TensorFlow / Keras

-Google Colab
