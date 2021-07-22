# TTGO-Watch-JPEG-SPIFFS
This is simply a demonstration of how Bodmer's  https://github.com/Bodmer/TFT_eSPI library can be used with the TTGO Watch 2020 v1
Rather than convert images, I had the need to dynamically load images to the watch and have them displayed.
To use this, the only requirment is a suitable JPEG image maximmum size 240x240px.

The code shows how one image is loaded, and has an example that cycles through all JPG in the SPIFFS "root".
![IMG_4513](https://user-images.githubusercontent.com/25142892/126584672-89ed8215-e5ff-4cb3-9e41-525151b05d9b.jpeg)
![IMG_4514](https://user-images.githubusercontent.com/25142892/126584683-005874ab-1653-4eca-85cd-1cc09695afc1.jpeg)

This code example loads a named image, then cycles through all JPEGs in the SPIFFS root.
