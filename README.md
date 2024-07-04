# Exploring Florence-2 Computer Vision Model on Colab with Streamlit UI

This project demonstrates how to use the Florence-2 computer vision model by Microsoft on Google Colab. The user interface is built using Streamlit, and tunneling is used to make the Streamlit UI accessible from Colab.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)

## Introduction
Florence-2 is a powerful computer vision model developed by Microsoft. This project explores its capabilities using Google Colab for computations and Streamlit for a user-friendly interface. The Colab environment is used to run the model, and the Streamlit UI is made accessible via tunneling.

## Features
- **Florence-2 Model**: Leverages Microsoft's Florence-2 model for computer vision tasks.
- **Streamlit UI**: Interactive user interface built with Streamlit.
- **Colab Integration**: Runs seamlessly on Google Colab.
- **Tunneling**: Access the Streamlit interface using tunneling techniques.

## Setup
To set up the project, follow these steps:

1. **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/MayurPimpude/Florence-2)
    cd Florence
    ```

2. **Run on Google Colab**
    Open the provided Colab notebook (`Florence2_Colab_Notebook.ipynb`) and run all cells. This will set up the environment, install necessary packages, and start the Streamlit server.

3. **Access the Streamlit UI**
    The notebook includes steps to create a tunnel using `ngrok` or a similar service to make the Streamlit UI accessible.

## Usage
1. **Upload Images**: Use the Streamlit interface to upload images for analysis.
2. **Model Inference**: The Florence-2 model will process the images and display results on the UI.

## Results

Here is Input UI:
![Screenshot 2024-07-03 143135](https://github.com/MayurPimpude/Florence-2/assets/100997225/7e9002e2-9362-4b3f-b2f4-58c6f13102c5)

Here are some examples of the model output:

### Simple Caption Grounding
![Screenshot 2024-07-03 143151](https://github.com/MayurPimpude/Florence-2/assets/100997225/56907432-a45f-4b17-b220-9eacf4421be3)

### Detailed Caption Grounding
![Screenshot 2024-07-03 143220](https://github.com/MayurPimpude/Florence-2/assets/100997225/687c64af-bd8b-4ca0-8d21-25822bb1e871)




