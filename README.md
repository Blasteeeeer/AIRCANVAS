# AIRCANVAS
Drawing in air with use of some object using openCV library

It will mask the object using SET_MARKER_HSV.py by taking the upper and lower value of HSV. It will save a numpy file having upper and lower value of hsv.
Using that range it mask the object and will find the contour of the object. Then using the origin of the object it saves the cordinates of the object in a numpy array.
Using all the co-ordinates store in numpy array we draw a line using openCV library.

we can change the color for drawing by selecting the color which is present in the top of the screen. It can be achieved by taking the object towrads it.
we can even erase the drawn image by selecting the eraser which is present in the top rigth of the screen.
