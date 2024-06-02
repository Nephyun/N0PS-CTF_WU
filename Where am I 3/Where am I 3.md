

## Nephyun - OSINT team     

## Where am I 3/3 WU

  

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/Where%20am%20I%203/images/image9.png)
  
  
  
  

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/Where%20am%20I%203/images/image1.png)
  
  

The challenge is accompanied by a jpg file, which we've included below.

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/Where%20am%20I%203/images/image2.jpg)
  
  

1). First, we tried to locate the country from which this photo was taken. Thanks to geospy.ai, we're in Japan. In addition, the signs on the ground suggest a country like Korea or Japan, while the structures on the right are more in the style of Japan. (The clue confirms the country).

  

2). After cleaning up the image (more or less) and focusing on a specific area, here's what we get : 

  
  

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/Where%20am%20I%203/images/image5.png)

  
  

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/Where%20am%20I%203/images/image7.png)

We have identified the following elements :

  

- A steel arch bridge with 8 or 9 beams
    
- A little red bridge in front of the one we're interested in
    
- A cable-stayed bridge in the background ?
    

  

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/Where%20am%20I%203/images/image8.png)

  
  
  
  

3). We've tried reverse image searches with Yandex, google, bing, yahoo ... with no conclusive results.

  
  
  

4). We've tried to list the bridges within 5km of a university with a castle nearby (as indicated in the hints, the distance is what we think is most likely according to the hints). 

- We used various websites listing castles and bridges in Japan (wikipedia ...).
    

  
  
  
  

5). After listing a huge number of bridges on google maps, we finally found a great candidate with all the features shown in the image !

  

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/Where%20am%20I%203/images/image4.png)

  

Scrolling down the map, we find our 2 barriers, and the sign on the road.

  

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/Where%20am%20I%203/images/image6.png)

  

6). Once these elements have been taken into account, we go to the 3D view of Google maps to validate the location. 

  
  
  

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/Where%20am%20I%203/images/image3.png)

  

6). The flag is the name of the bridge behind the photographer. 

**Flag : N0PS{toyamao-bridge}**

