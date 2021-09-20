1. SHINE YOUR EYE


oops there's Nothing Intresting at the website Interface Since they ask us to Shine our eyes Lol 
let's take a Look at the source code:
![Sources](https://user-images.githubusercontent.com/53369822/134006732-cf624ab6-df47-49e2-a556-7e7fe7af07a9.jpg)
From the source code above I saw a javascript link which catch my eye Seems am shining my eye LOl.
i followed the link to see what's there Boom I found something:
![Js](https://user-images.githubusercontent.com/53369822/134007439-28dcf291-9dd3-41c6-abad-c775ba26d312.jpg)


Look at what I got let's copy that out and paste on our web browser:

from the path I got a base64 encoding Let's Decode it 
Decoding it reveal the flag for us

![flag1](https://user-images.githubusercontent.com/53369822/134007624-80d49470-117d-4bc4-a44d-18bffe01936f.jpg)


2. INDEXING 

This Looks more difficult but let's check for the robots.txt directory If we can find something Intresting 
![Robot](https://user-images.githubusercontent.com/53369822/134008479-1cbbe9b6-1281-48f2-b5e0-f2d7ef9bbece.jpg)

Good seems we are getting there gradually Let's checkout the /img/Finaflag.png
Let's go to the path and see:

![file](https://user-images.githubusercontent.com/53369822/134009200-a9e8d6da-cd41-4476-94ea-9c5ae485962c.jpg)

But the image cannot be display Why not use Wget to extract the Image:

![flag](https://user-images.githubusercontent.com/53369822/134009420-a4f97bb8-e5d5-4181-bd24-68877c14c46b.png)

Two things happened from the above screenshot 

First: i used wget to extract the picture from the website but when i open the pic not display yet 

Second: I decided to check the strings format of the picture Sometimes flags are usually hide there 
checking the strings of the png I go an encoded text analyzing it reveal that it's an ASCII 
I decode it using ASCII online decoder and it reveal the flag 
![image](https://user-images.githubusercontent.com/53369822/134010456-3693d63e-0c8c-4928-9a5d-726db49a0418.png)





