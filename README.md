spark-core-web-page-html-control
================================

Example control of the spark core and perhaps photon with a simple html web page 



Dec 12, 2014  Can't really believe that it worked, but it does. You need to find your access token in the spark settings page at the bottom left of your spark IDE screen.

You then need the Core Device ID which is harder to find. You have to go to the core then click on your cores ">" sign beside the flashing blue dot.

Then just call the function you want to activate. Travels at the speed of your connection which can be fast or up to a few seconds.


Wow. Very happy.

Jan 4th, 2015



So files:

spark-control-basic-web-page.html Control a spark device using regular html a form, iframe and local storage. 

spark-wen.ino the spark file that must be flashed to the device

useless.ino  the bare essential spark activation but uses up the four possible spark functions. Simple but useless

xtra-ajax-json-slider-polling.html   a more advanced much better than the basic web page still only uses javascript and html but is more efficient.

Both HTML files can be loaded onto phonegap build to make Android and iOS Apps that activate spark devices.





