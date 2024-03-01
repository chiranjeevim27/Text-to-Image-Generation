# Diffusion Pipeline for Image Generation

## Overview
This repository contains code that utilizes the `diffusers` library to generate images based on textual prompts. The pipeline uses a pre-trained model and is optimized for GPU acceleration.

## Dependencies
- Python 3.x
- [diffusers](https://github.com/example/diffusers) (version 0.21.4)
- [transformers](https://github.com/huggingface/transformers)
- [scipy](https://github.com/scipy/scipy)
- [ftfy](https://github.com/LuminosoInsight/python-ftfy)
- [accelerate](https://github.com/huggingface/accelerate)
- [wcwidth](https://github.com/jquast/wcwidth) (version 0.2.12)
- [torch](https://github.com/pytorch/pytorch)

## Installation
```bash
pip install diffusers==0.21.4
pip install transformers scipy ftfy accelerate wcwidth==0.2.12
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/chiranjeevim27/Text-to-Image-Generation.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the provided script:
   ```python
   python Text-to-Image generation.ipynb
   ```

   Follow the prompts to input text and generate corresponding images. The script saves the generated images in the current directory.

## GPU Configuration
Make sure to have a compatible GPU and install the necessary CUDA toolkit. Adjust the batch size and other parameters in the script based on your GPU capacity.

## Acknowledgments
- This project uses the `stabilityai/stable-diffusion-xl-base-1.0` model provided by [stabilityai](https://github.com/stabilityai).

## License
This project is licensed under the [MIT License](LICENSE).
