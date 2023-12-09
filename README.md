# GoogleKeep
Google keep  Application with localStorge

Hii Everyone My Name Is Rupesh And This Is a simple Application to write and save text permanently until you forcefully delet it.

LET'S SEE HOW CODE IS WORKING

1 : Basic Implementation : Inject html code on click of new button and save text if users writes on local storage .

2 : We need Small tex boxes in which we can write anything edit and save for this i have used grid in one row max three boxes can be 
    added , we will inject this box on click on new button on top right corner
    html class and css code for this
   
   <div class="grd-note-area grd-3c rw-gap-1r">  add div on click  </div>
   
3 : by button click  new div class name note-area will be added ininside above div grd-note

4 : we have two operation buttons edit and delete when cliked outside of box or pressed edit button we have set textarea elemet to 
    disabled by toggle
    textArea.toggleAttribute("disabled");

5: Finally on refresh or late when page is reloaded we retrieve data from localStorage and set to To boxes 

IMAGES 
![Screenshot (40)](https://github.com/viperven/GoogleKeep/assets/127649834/194c961c-8444-4049-8bad-3726fcd9ab79)

