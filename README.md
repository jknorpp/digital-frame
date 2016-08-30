# digital-frame
Additional software for a digital media frame using a raspberry pi 3.

This software package combines bits of code found on the web.


## flickr_download.sh

Follow this tutorial to install all components needed on your Pi to run flickr_download: http://learningthings.info/index.php/2016/07/25/learning-to-download-flickr-photos-using-python-and-flickrapi/

flickr_download calls the script  
-k <api key> sets public API-key  
-s <api secret> sets secret key  
-d <set id> defines the album (or set) of Flickr Stream you want to download  
-t calls for authentication  

## slideshow.sh

Follow this tutorial to install all components needed on your Pi tu run framebuffer imageviewer (fbi):
http://www.queryadmin.com/435/create-image-slideshow-raspberry-pi/
See also: http://manpages.ubuntu.com/manpages/xenial/en/man1/fbi.1.html

fbi calls the script to show the slideshow  
-noverbose hides the status line  
-a zooms pictures to screen size (take care to provide pictures that are large enough)  
-u shows pictures in random order  
-t sets the time for each picture to be shown (in sec)  
/yourpicturefolder/* shows all pictures in the specified folder  
