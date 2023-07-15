In this post, we want to compute the area of Annecy Lake using accept rejct sample algorithm, described : [[Accept - Reject Sample Algorithm]] !
![[annec_pic.jpg]]


Here is the pic I screen shotted in Maps : 
![[Capture d’écran 2023-07-15 à 16.00.43.png]]
The process is pretty straight forward : gerenate random points  across the picture, and take only the ones in lake. 
The main difficulty was to find a good criteria to see whether the pixels were lake pixels or not. A decision tree good be done here...![[Capture d’écran 2023-07-15 à 18.43.49.png]]Given to total area of the picture, you can easily recover the area of the lake. ![[Capture d’écran 2023-07-15 à 18.44.04.png]]

We get the picture as a result : 
![[Monte_Carlo_Lake.png]]

Quite happily enough, our value stands quite close to the real one of Wikipedia : 27.59 km2
https://en.wikipedia.org/wiki/Lake_Annecy
even tough we can se on the picture that there are some green points in the non-lake zone (especially near the bottom-left corner), my criteria here could definitely get better. 

I'll finish with this nice picture this house of my cousins' friends where I was lucky enough to go .. there are some people on this beautiful planet who are not to be pitied ! 


![[359772668_6241036102662241_1218709484030522117_n 1.jpg]]