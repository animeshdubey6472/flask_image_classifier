## Model Weights (Important)

The trained VGG19 model file is not included in this repository due to GitHub size limits.

To run the app locally:
1. Obtain a VGG19 `.h5` model (ImageNet or trained)
2. Place it inside the `model/` directory as `vgg19.h5`

## How It Works
- Flask handles routing and image uploads
- TensorFlow/Keras performs inference using VGG19
- Frontend uses HTML/CSS/JS with AJAX for predictions
