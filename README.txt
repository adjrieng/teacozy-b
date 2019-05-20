Hello to whomever will be analyzing my work.

I want to preface by saying I did change a few things in the exercise to make the final product look more like the 
mock-up image. Further, I also added an element of modularity for my fictional client as it were (I found this gave 
me a little extra challenge to really work with flex and better understand it). *Please note, if there are "points"
taken away for not following the assignment instructions to a T please let me know and I will resubmit.

With that said, the firtst thing you will notice is that the spans on the inventory pictures are not black... I did
this to call your attention to them on purpose. If you look in the CSS file you will note the following;

1) I colored the inventory label spans using rgba (allowing for greater colors and the use of transparency for the 
span without impacting the text). This is deactivated with 1 mouse click and they will be black (per the exercise). 

2) The inventory section allows the developer to easily change the vertical positioning of the label span by taking
the following actions; 
	
	1) in the CSS file (or live in debug...) comment out (unclick) the "margin-bottom: -250px" and you will see
	that the label span will center itself vertically in the respective inventory image. 
	
	2) once the above margin has been deactivated you can then change the "justify-content" value on "inv-box" 
	in the CSS file to either "flex-end" or "flex-start" to see the label span either hug the top of the or 
	stradle the base inventory image. *By doing it in this way, I have given the "client" 4 ways to layout their
	goods. 


*** Only difference is how the footer is handle *** 


again. just having fun while learning. thanks!