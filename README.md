# TTGO-Watch-JPEG-SPIFFS
This is simply a demonstration of how Bodmer's  https://github.com/Bodmer/TFT_eSPI library can be used with the TTGO Watch 2020 v1
Rather than convert images to C arrays, I had the need to dynamically load images to the watch and have them displayed.
To use this, the only requirment is a suitable JPEG image maximmum size 240x240px.

The code shows how one image is loaded, and has an example that cycles through all JPG in the SPIFFS "root".

![IMG_4513](https://user-images.githubusercontent.com/25142892/126589242-091c8f37-b97a-40e9-80af-50b115214f59.jpeg)
![IMG_4514](https://user-images.githubusercontent.com/25142892/126589245-f816f653-196a-40a2-b239-bd3223ee9e37.jpeg)


This code example loads a named image, then cycles through all JPEGs in the SPIFFS root.
