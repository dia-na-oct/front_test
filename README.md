# 30-sep
<!--this readme file is for learning position and basics in css-->
conflicts: id(100)==>class(10)==>element(1)==>specificities==> order
inheritance:every selector inherit from his parent
to target mutiple element ==> li , span ,....
to target exact children so we dont want other children ==> parent>child
target adjacent element h1+p{}==> means color the p that is after the h1 in the code
psudo(behavioural like hover, active,visited or structural ) class for example hover ==> .class-name:hover{}
structural like  article p:first-of-type {} mean that the first child of article who is an p
combining selectors ==> article.awesome{}==> article that have this classe 
the univaersal selector * herit for his children every thing not lie the body.
a*4{hello}[href="#"]
height =70% its responsive tae 70% from his parent 

font size em=herit the parent and multiply it by 3 for example, % from the parent
la diff entre inline (occupe l'escpace qui le suffit , dans la meme ligne mais ilya tjrs un problme
de chauvachement donc on utilise inline-block) block (accupe tous l'espace de son parent , un devant l'autre)
pout mettre image background on a background position , size repeat....

<!---lets start new lessons about flexbox-->
container that we made flex, all its child became flex, so 
we can control its behaviour (if they are in top of each other.....)
ifi make display of container flex is the same result as making its children float left then clear after this container
flex-grow: how element come bigger for each other 1,2 double 
flex-shrink: when we make the screen smaller than the width of their parent how elements gonna be , <!--rarely-->
