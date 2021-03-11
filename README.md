# PyToch - View Conv Layer Effects

## How to see what the convolution layer is learning about an image:

1. Take conv layer weights
2. Convert them to numpy
3. Load a sample image from test set
4. For all layers of filter:   
a. apply ith filter using cv2.filter2d    
b. show filtered image using plt.imshow

![Effects](./conv-effect.png)