# PhotogrammetryTools
Tools to assist in Photogrammetric processing

By: Jan Erik

## Intructions

### [1] Required Libraries
Make sure your environmental variables include the following libraries:

cv2 | numpy | pandas | os

### [2] Folder Structure
Drag PointFinder.ipynb into the folder that your images are in. In this example we will use test.jpg but you can also have more than one image in the folder so please don't waste time making a folder for each image :-)

![image](https://user-images.githubusercontent.com/60162470/138387158-3c6b90e3-c5e4-44d3-b277-b81091f34b83.png)

### [3] Opening the file
It is reccomended to open this file within Jupyter notebook. 

I tried making it into a .py file but when I imported and ran it the GUI wasn't appearing :-(

Opening "PointFinder.ipynb" will contain two cells. The first contains required classes and the second cell is where we'll run things, it should look like:

![image](https://user-images.githubusercontent.com/60162470/138386334-8cb3e980-47f6-4742-aee0-4e58d4fae98a.png)

### [4] Picking your object point selection order
You will pass in your object point selection order as a list of numbers. If you were going to pick three points AVS12, AVS23, AVS14 in that order then you would pass it in like this:

![image](https://user-images.githubusercontent.com/60162470/138386680-0a84a5b4-7347-4ebe-a926-64fac71522fc.png)

#### Note: 
All points are concated with the string AVS before the number value for your convenience. Sorry that means that AS points are a pain to use (I reccomend you use them)

If you do not input a list then the default order is as follows:

![image](https://user-images.githubusercontent.com/60162470/138387930-02c77963-490d-4d2b-b0ee-f7ace3ed10d5.png)

### [5] Picking your image file
If your image was called img1.jpg your second cell would look like:

![image](https://user-images.githubusercontent.com/60162470/138387457-0d0644ee-adca-4289-8b1c-a410394eda10.png)

### [6] Running Point Selector
Now you can run the first and second cell. Once the second cell runs look for a white paper in your task bar and open it to go to the GUI

![image](https://user-images.githubusercontent.com/60162470/138388060-76dd92a2-7a52-46f8-a283-4eafc3eae5e3.png)

If you run the default PointSelector("test.jpg") and the test image is in the folder then it should look like this:

![image](https://user-images.githubusercontent.com/60162470/138388155-38ef0553-80f8-4220-8eb5-4a2c5b17c214.png)

### [7] Selecting Points
1. right-drag up or down to zoom
2. right-click to center the view on the mouse
3. drag the x and y trackbars to scroll
4. left click to select a circle center

![image](https://user-images.githubusercontent.com/60162470/138388537-dd93f5e3-db50-4a92-bc99-301d1e89ac6e.png)

5. to delete the previous point from the file that will be saved click the 'p' key (you'll know its value deleted because the next point you click will have the same index value)

![image](https://user-images.githubusercontent.com/60162470/138388648-e4ae72e3-9d51-4921-bbba-56fdc191e7d4.png)

6. to save your values you must click the 'q' or 'Esc' keys. Clicking the 'x' on the GUI will not save your image

### [8] Output
A "Points" folder will be created to store the output values. For each round of point selection this will imclude the output image and a .csv file of the circle centers.

![image](https://user-images.githubusercontent.com/60162470/138388819-0cbda6eb-2b02-4811-ab29-e69372525f7c.png)

It is reccomended to use the output image for detecting blunders

### Enjoy!
#### If you found this tool useful please star and watch this GitHub repository and follow my GitHub account

![image](https://user-images.githubusercontent.com/60162470/138389077-44635185-c5ad-46cd-a514-a827378889be.png)

## Thanks!


