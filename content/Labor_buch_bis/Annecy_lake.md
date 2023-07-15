
![Intro_Pic](pictures/annecy_pic.jpg)



In this post, we want to compute the area of Annecy Lake using accept rejct sample algorithm, described : [[Accept - Reject Sample Algorithm]] 
Here is the pic I screen shotted in Maps : 
![original_pic](pictures/Original_pic.png)
The process is pretty straight forward : gerenate random points  across the picture, and take only the ones in lake. 
The main difficulty was to find a good criteria to see whether the pixels were lake pixels or not. A decision tree good be done here...![screen_1](pictures/Screen_1.png)Given to total area of the picture, you can easily recover the area of the lake. 
![screen1](pictures/screen_1.png)

We get the picture as a result : 
![screen2](pictures/Monte_Carlo_Lake.png)

Quite happily enough, our value stands quite close to the real one of Wikipedia : 27.59 km2
https://en.wikipedia.org/wiki/Lake_Annecy
even tough we can se on the picture that there are some green points in the non-lake zone (especially near the bottom-left corner), my criteria here could definitely get better. 

I'll finish with this nice picture this house of my cousins' friends where I was lucky enough to go .. there are some people on this beautiful planet who are not to be pitied ! 


![finale_pic](pictures/final_pic.jpg)
