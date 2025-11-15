# Streamlit Style Transfer App

An interactive deep learning web app built with **Streamlit** and **PyTorch** to apply **style transfer** to images.

## References
This app is based on the official PyTorch example:

- **Fast Neural Style**  
  https://github.com/pytorch/examples/tree/main/fast_neural_style  

And uses Streamlit for the frontend:

- **Streamlit**  
  https://streamlit.io


## Installation

It is recommended to use a virtual environment and install the required packages:

```bash
pip install streamlit
pip install torch torchvision
```

## Usage
Download the pretrained models

```bash
python download_saved_models.py
```
Move the saved_models folder into the neural_style folder.

Run

```bash
streamlit run main.py
```