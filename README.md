# Document_Rectification

`$ROOT/distorted/` folder contains distorted document images that needs rectification.

`$ROOT/rectified/` folder contains rectified image after the inference.

`$ROOT/data/` folder contains distorted document images.



# Inference:

Step 1: Put the pre-trained model in the `$ROOT/model_pretrained/` folder.

Step 2: Put the distorted images in the `$ROOT/distorted/` folder.

Step 3: Run the below script and the rectified images will be saved in `$ROOT/rectified/` folder by default.

  
    python inference.py
