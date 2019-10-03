# Colorblind Plugin

Libraries:
OpenCv
path: "lib/opencv"


Method 1: findConflict()
IN:  Mat image (bgr-format som default)
OUT: List<Rect>


Method 2:
getFilteredImage(img, rectList, new Point());
IN: *Mat image
    *List<Rect>  //from findConflicts()
    *Point(x,y)  //from mouse click    


OBS!
* Change 'projectPath' field in ColorPlugin.java
* 'logger' field set to true for image saving, easy debugging.
  false default to minimize execution time
* 'minRectArea' field, default 2500, size of minimal rect area to ignore noises 
  

# PRESENTATION
  
![](info/ColorblindPlugin_presentation (1).PNG)  
![](info/ColorblindPlugin_presentation (2).png)  
![](info/ColorblindPlugin_presentation (3).png)  
![](info/ColorblindPlugin_presentation (4).png)  
![](info/ColorblindPlugin_presentation (5).png)  
![](info/ColorblindPlugin_presentation (6).png)  
![](info/ColorblindPlugin_presentation (7).png)  
![](info/ColorblindPlugin_presentation (8).png)  
![](info/ColorblindPlugin_presentation (9).png)  
![](info/ColorblindPlugin_presentation (10).png)  
![](info/ColorblindPlugin_presentation (11).png)  
![](info/ColorblindPlugin_presentation (12).png)  
![](info/ColorblindPlugin_presentation (13).png)  
![](info/ColorblindPlugin_presentation (14).png)  
