# Colorblind Plugin
@author Maksym Gorbunov


Libraries:
OpenCv
path: "lib/opencv"


Method 1: findConflict()
Find color conflict and mark areas which are difficult for color blind peoples to se
IN:  Mat image (bgr-format som default)
OUT: List<Rect>


Method 2:
Filter matched area, show how color blind people se 
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
  
![](info/ColorblindPlugin_presentation_(1).png)  

![](info/ColorblindPlugin_presentation_(2).png)  

![](info/ColorblindPlugin_presentation_(3).png)  

![](info/ColorblindPlugin_presentation_(4).png)  

![](info/ColorblindPlugin_presentation_(5).png)  

![](info/ColorblindPlugin_presentation_(6).png)  

![](info/ColorblindPlugin_presentation_(7).png)  

![](info/ColorblindPlugin_presentation_(8).png)  

![](info/ColorblindPlugin_presentation_(9).png)  

![](info/ColorblindPlugin_presentation_(10).png)  

![](info/ColorblindPlugin_presentation_(11).png)  

![](info/ColorblindPlugin_presentation_(12).png)  

![](info/ColorblindPlugin_presentation_(13).png)  

![](info/ColorblindPlugin_presentation_(14).png)  
