# Image Generation
cd image_generation
## Step 1: Train image generation model 
sh train.sh 
## Step 2: Generate additional images
sh generate.sh 
## Step 3: Add generated images to training set
# Face Expression Recognition
cd face_expression_recognition
## Step 1: Train face recognition model
sh train_face.sh
## Step 2: Test face recognition model
sh test_face.sh
