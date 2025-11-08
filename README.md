# ESPHome_CYD
ESPHome on a CYD with LVGL Graphics

# Project
So I decided to dive into programming up a CYD (Cheap Yellow Display - ESP32-2432S028R) Using LVGL as the graphics library, and ESPHome. 
This was a difficult project, as there is not a lot of documentation out there, or even really good examples to go off of. 
The display handles the basics I needed for a bedside control surface.   

There is a single YAML file here, and that is the in-use code for the CYD.  
I will try and make sure I have a lot of comments, so hopefully it makes some sense to someone trying to replicate!

# Layout
There are 3 pages, the first being 6 basic control buttons, to control lights in my smart home that I typically need to make sure are off when I go to bed. Things like the back yard lights, garage light, etc.  
I also have my AdGuard enable on there as well, as my wife likes to disable it from time to time, so she can earn rewards on some of her mobile games, by watching ads. This way, I can turn it back on before we go to bed.  
There is also a "Top Layer" that has navigation at the bottom, and the time/temp at the top. These span all three pages.  
The second page just has some relevant info that I may need to see, such as outside temp, server power draw, etc.
The third page, is the one that stays up on my office CYD, and it has two basic buttons, and some data displayed from my router. 

# Pictures
