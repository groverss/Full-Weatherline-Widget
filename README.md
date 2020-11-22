# Full-Weatherline-Widget

<p align="center" >
    <img width="500" alt="Full-Weatherline-Widget" src ="./5964BDCB-2029-4FA1-AE2B-A0CE429662A5.jpeg">
</p>

A proffesional large and medium Weatherline widget for your glory screen, it has hours of day and 7 days of week with minimal weather info below. Colorful lines for either increase or decrease of your weather at any hour. With dynamic light/dark background or a preferable photo as transparent one. it has localization for any language.



Update 1: Now supports offline mode without internet connection.

Update 2: Opacity has been fixed, go to line 270 to 287.

Update 3: Added Medium size, added 12 hour mode, added external  redirected link, fixed offline icon size, fixed sunrise and sunset issues and a lot of bugs fixed. 

Update 4: Added 12 hour for diagram.

Instruction:

1. Put your API code from openweathermap.org at Line 14.
2. Set locale language code at Line 17 (Please pay attention if you set this, the language of "city name" will be in your native language after step 3)
3. Turn on your "Location Services" for reading the name of city and for once and forever, you can turn it off after loading.
4. Screen Size:

if you are on large screen dievices such as Pro Max, XS Max, even XR, set the widget size according to:

Line 307: widget.padding = 0

if you are on old and small devices (like me :D ), don't need to change anything.

5. Widget has dynamic background for morning, afternoon and night and for setting this mode, you should do this:

Line 25: const imageBackground = false

And for using your gallery photos as a transparent type, do as:

Line 25: const imageBackground = true
Line 29: const forceImageUpdate = true

and after your selected proper photo: 

Line 29: const forceImageUpdate = false

6. Weather unit:

Line 253: units: "Metric"
          units: "Fahrenheit"
          units: "Imperial"
          
          
7. Line 35: HoursToShow : number > Number of predicted hours to show, Eg: 3 = a total of 4 hours in the widget (Default: 3 for the small and 11 for the medium one but to be shown in the Large size only).
 
const hoursToShow = 9

const daysToShow = 6   

8. Line 49: 12 Hours : 12 or 24?
    and                diagram12Hours = ?!

9. Line 55: Open Link for adding your preferable link.
          
          
          
Workable Widget Size: Large, Medium.

Note: The widget preview is for dev only, so ignore it if see something unusual. 
