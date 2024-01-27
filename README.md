# Neural Style Transfer

## Description
Head to the colab notebook - <a href="https://colab.research.google.com/drive/1VRLnlUGP0J8Em4DQRr8eJUd6fSxpiPnB?usp=sharing">colab link </a>

Applied computer vision techniques to seamlessly transfer artistic styles from one image to another using neural networks. This project leverages deep learning and transfer learning with the VGG-19 model.

## How It Works

Neural Style Transfer (NST) combines the content of one image with the style of another, creating visually striking compositions. The VGG-19 model extracts features, and loss functions are employed to optimize the generated image to match the desired style while preserving the original content.

## Tools Used

- Python
- TensorFlow
- Matplotlib
- PIL (Pillow)
- NumPy
- Git
- GitHub
- Numpy

## How it Works
1. **Load and Preprocess Images:**
   - Load content and style images.
   - Resize for consistent processing.

2. **Load Pretrained VGG-19 Model:**
   - Utilize VGG-19 as a feature extractor.

3. **Define Content and Style Layers:**
   - Identify layers for content and style.

4. **Compute Content Cost:**
   - Extract features from content layer.
   - Compute content cost.

5. **Compute Style Cost:**
   - Extract features from multiple style layers.
   - Use Gram matrices for style representation.
   - Compute style cost.

6. **Define Total Cost and Optimize:**
   - Combine content and style costs with weights.
   - Optimize generated image.
<b>More details are present in the colab</b>

# Output-
![image](https://github.com/Taha0229/neural-style-transfer/assets/113607983/03d8fa84-0d6d-4054-83e4-cc4bb7eaef86)
![image](https://github.com/Taha0229/neural-style-transfer/assets/113607983/11c44201-0a40-49d1-82fa-fca323f22dee)
![image](https://github.com/Taha0229/neural-style-transfer/assets/113607983/4ea0ace3-9690-42c4-b7b1-f111d5d0ac87)
![image](https://github.com/Taha0229/neural-style-transfer/assets/113607983/f5a5cbca-5228-45bc-aa06-a197d4758513)
![image](https://github.com/Taha0229/neural-style-transfer/assets/113607983/255eef4b-9bb1-4d2b-a675-5d6520233192)





