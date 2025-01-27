# barnacle-detection


## Barnacle Detection

### Libraries Used

```c 
numpy

opencv-python

matplotlib

```
### Process

```
1. Preprocessing

The input image was converted to grayscale to simplify processing. I also used Gaussian Blurring to reduce noise, allowing for smoother detection of circles.

Grayscale Conversion: Converts the image from BGR to  grayscale.

Blurring: Uses Gaussian blur to reduce noise.

2. Circle Detection

Hough Circle Transform algorithm was applied to detect circular regions in the image. I experimented with the radius to determine the best value for the circles. 

3. Visualizing Results

The detected circles were drawn on the original image using the cv2.circle function. 


```
### Use and Future Extensions

``` 
I tested the program on both unseen images. Either one can be detected by changing which image is loaded into the program. The modified images are displayed in the notebook. 

Future: I would aim to incorporate green frame detection by utilizing HSV detection to only analyze the area inside it. I would also want to use contour filtering to improve the accuracy of the program. 

```

        
    
