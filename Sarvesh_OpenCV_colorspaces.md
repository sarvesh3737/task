# **COLOR SPACES IN OPENCV**
  **Basically it is a way to represent colors in an image that gives it a shade.
  In OpenCV there are three color spaces i.e BGR,CMYK,HSV.Every color space has its separate role.**
  
  
  # 1.BGR(Blue,Green,Red):-
  **a.In this color space the different intensities of the blue,green,red give us different shades.<br />
     b.It is an additive color space. e.g:addition of red to green gives us yellow shade.<br />
     c.Default color space of OpenCV is RGB.**<br />
     
  
  # 2.HSV(Hue,Saturation,Value):-
  **a.Hue is the color,Saturation is the greyness,Value is the brightness of the pixel.<br />
    b.This color representation is stored in cylindrical format.<br />
    c.Range of HUE is 0-179,SATURATION is 0-255,VALUE is 0-255.**<br />
    
    
  # 3.CMYK(CYAN,MAGENTA,YELLOW,BLACK):-
  **a.It is a substractive color space.<br/>
    b.By substractive it means that white light is removed from the base colors i.e blue ,green and red.<br/>
    eg:-if we take away white light from green we get Magenta and similarly for other colors.**<br/>
  
