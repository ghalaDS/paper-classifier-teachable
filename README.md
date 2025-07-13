# paper-classifier-teachable
This project classifies different types of paper using a Teachable Machine image model. The model identifies whether the uploaded image is **Lined, Grid, Dotted, or Plain** paper. It's deployed and tested in Google Colab using TensorFlow and Keras.

---

![Sample Output](./Screenshot%202025-07-12%20150128.png)

---

## Files

- `keras_model.h5` — Pre-trained model from Teachable Machine  
- `labels.txt` — Contains the paper type labels  
- `my_image.jpg` — The paper image to be classified  
- `classifier.ipynb` — Python notebook for running predictions  

---

## How to Use (in Google Colab)

1. Upload the following files into Colab:
   - `keras_model.h5`
   - `labels.txt`
   - `your_image.jpg`

2. Install TensorFlow (if needed):

```python
!pip install tensorflow==2.12.1
Paste and run the notebook code.
