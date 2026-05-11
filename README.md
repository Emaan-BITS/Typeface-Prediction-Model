<h1 style="text-align: center; font-weight: bold; color: white; text-decoration: underline; font-variant: small-caps;">Deep Learning based Typeface Recognition</h1>

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://typeface-prediction-model.streamlit.app/)

Deep Learning based model to predict the Typeface used in a given image.

[Click here](https://typeface-prediction-model.streamlit.app/) for an interactive front-end demo.

The "[Demo samples](https://github.com/Emaan-BITS/Typeface-Prediction-Model/tree/main/Demo%20samples)" folder contains sample images, which can be
used to test the model.

# **Model**

The model has an accuracy of **78.02%** in predicting the typeface used.

Shown below is a Confusion Matrix for the letter `P` rendered using all
typefaces. The y-axis denotes the Typeface used, and the x-axis denotes the
prediction by the model. The near-perfect diagonal line indicates that the model
is **very accurate** in predicting the typeface used for the given letter.

<img src="README - confusion matrix.png"/>

Shown below is the model architecture:

<img src="README - architecture.png" width="1000px"/>

---

# **Environment setup**

This project has been tested with Python 3.12.

1. Create an environment:

   ...using `venv`:
   ```bash
   python -m venv venv
   ```

   ...using `conda`:
   ```bash
   conda create -n typeface-recognition python=3.12
   ```

   ...or using any other environment manager of your choice.

2. Install PyTorch, as per the [official instructions](https://pytorch.org/get-started/locally/#start-locally).

3. Install remaining requirements:

   ```bash
   pip install -r requirements.txt
   ```
