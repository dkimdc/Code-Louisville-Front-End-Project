# CodeLou_FrontEnd

## Description
```
This project is the beginning of a webpage for my son. The main page has a large photo
and a short introduction. If you click on Photos in the navbar, you will see 6 photos.
If you click on any of the photos, a larger version of the photo will appear and the 6 smaller photos will fade. Click the larger image to make it disappear and the 6 smaller photos will be bright again. The main page and photo page use bootstrap and media
queries for different sized displays.





## Custom CSS Classes
```
The class(es) I created are:

1. .main-row
    Sets display to block and adds padding around the text and photo on the main page.

2. .main-col-intro
    Sets background color to green; font to Verdana; centers text; assigns flex value of 1; width of 100% to Intro paragraph on left side main page.

3. .main-col-photo
    Assigns flex value of 1; width of 100% to large photo on right side of main page.

4. .col
    Sets padding around photos; assigns flex value of 1; assign minimum width to photos on photo page

5. .row
    Sets display value and width based on screen size; sets flex-wrap to wrap; assign space-around the photos on photo page

6. photo-header
    Set max-width for title at the top of the photos page; Set left margin




## Custom JavaScript Functions
```
The javascript functions I created are:


1. function showImage(imgName) 
    This function assigns the photo clicked to be the large image.
   
2. function showLargeImagePanel() 
    This function makes the large version of the image visible.

3. function unselectAll()
    This function unselects all the photos.

4. function hideMe(obj) 
    This function hides the larger version of the image when it is clicked.