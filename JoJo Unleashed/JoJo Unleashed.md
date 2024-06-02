

## Nephyun - OSINT team     

## Jojo Unleashed WU

  

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image12.png)

  
  
  
  

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image8.png)

  

1). One of the first thing we did was to check the EXIF data in the file, which gave us an interesting information 

|                   |                                                                                                                                                 |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| QuickTime:Comment | Our meeting will be in a castle at the east of the first location mentioned in the song and named after its full name. Be careful Js! See ya ;) |

2). By typing some of the words heard in the song, we can find the name of the song and the full lyrics 

[https://www.musixmatch.com/lyrics/Jacques-Brel/Jojo](https://www.musixmatch.com/lyrics/Jacques-Brel/Jojo)

  
  

3). The first location mentioned is Saint-Cast short for Saint-Cast-le-Guildo

[https://fr.wikipedia.org/wiki/Saint-Cast-le-Guildo](https://fr.wikipedia.org/wiki/Saint-Cast-le-Guildo)

  

4). On Google Maps we can see a castle at the east of Saint-Cast with a strange review on Tripadvisor

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image3.png)

[https://www.tripadvisor.com/Profile/justineJB123](https://www.tripadvisor.com/Profile/justineJB123)

  
  

5). Her intro gives us an email which we will then use to check her google calendar 

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image6.png)

  
  

6). On the calendar we can find the date of the final meeting and a new pseudo

[https://calendar.google.com/calendar/u/0/embed?src=jorabetagnyjustine@gmail.com](https://calendar.google.com/calendar/u/0/embed?src=jorabetagnyjustine@gmail.com)

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image13.png)

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image1.png)

  

7). We then try to find where this username is used and we get a github account with a link to a website   

[https://www.digitalfootprintcheck.com/free-checker.html](https://www.digitalfootprintcheck.com/free-checker.html)

https://github.com/trebogosse

[https://trebogosse.github.io/trepogosse/](https://trebogosse.github.io/trepogosse/)

  

8). It is apparently the second version of his website, the first one is not on his github but can be found on wayback machine, this new version give us a new pseudo “Janette Voibien”

[web.archive.org/web/20240504194028/https://trebogosse.github.io/trepogosse/](http://web.archive.org/web/20240504194028/https://trebogosse.github.io/trepogosse/)

  

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image7.png)

9). Thanks to this pseudo, we find her on Facebook, where we can see a post with lots of informations 

[https://www.facebook.com/profile.php?id=61559613950990](https://www.facebook.com/profile.php?id=61559613950990)

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image9.png)

  

10). With geospy.ai and a reverse image search we can determine that the picture was taken somewhere in Tunisia, Tunis-Carthage international airport being the only airport close to a landscape similar to the one on the photo. We now only have to explore the beaches near Tunis to find the exact location and therefore confirm our hypothesis about Tunis-Carthage airport

[https://www.google.com/maps/@36.9361575,10.2585761,985m/data=!3m1!1e3?entry=ttu](https://www.google.com/maps/@36.9361575,10.2585761,985m/data=!3m1!1e3?entry=ttu)

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image5.png)

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image10.png)

  

11). We now know that she took a flight from Tunis-Cartage airport [10], early in the morning of  05/23/2024, with a time difference of only 1 hour between the two countries  and an approximate duration of 1h30 [9]. A few flights meet these requirements but all of them are in France

[https://www.flightera.net/en/airport/Tunis/DTTA/departure/2024-05-23%20%2000_00](https://www.flightera.net/en/airport/Tunis/DTTA/departure/2024-05-23%20%2000_00)

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image11.png)

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image2.png)

  

12). We search “Pointe de l’aiguille” and quickly find a place on google maps near Nice, which is one of our possible flights, the location of this place being “Theoule-sur-mer” and the one we were looking for

https://www.google.com/maps/place/Pointe+de+l'Aiguille/@43.5062646,6.9431933,3568m/data=!3m2!1e3!4b1!4m6!3m5!1s0x12ce837ccea4ef05:0xe7a5289c9e28a4b3!8m2!3d43.50625!4d6.953493!16s%2Fg%2F1q5blp5s3?entry=ttu

  

![](https://github.com/Nephyun/N0PS-CTF_WU_Osint/blob/main/JoJo%20Unleashed/images/image4.png)

  

**Flag : N0PS{03-06-2024_theoule-sur-mer}**

