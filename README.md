# Refactor-Landing-Page
Here is the screenshot of the Horiseon Main Page and its url. Bugs and fixes explantion will be at the very bottom.

![alt text!] (file:///Users/dankim/Desktop/Homework/Refactor-Landing-Page/index.html)




















*Update 1.0*
1. To follow proper semantic approach for the html file, most of the <div> were changed into a more meaningful element like main, section, aside, etc. 
2. Was not able to change the "hero" section because the picture needed configuration to fit the webpage on the css file. Instead of using "img", the <div> was kept; however, the "alt", or in this case, "title" was implemented in order to have a description just in case the image does not load.
3. Speaking of which, all images have the "alt" function. 
4. Because a lot of changes occured in the html semantics, it had to be translated accordingly in the css file. For example, because <div class> was changed into "section", the css file changed from ".class" to "section"; it changed from a class to an element.
5. Many properties were consolidated within the css file, as many were the same within the same sections. In one instance, a class was changed into "benefit-child", because three of the child had the same properties in the css. Instead of keeping the redundancies, it was better to reduce it in order to keep productivity high and per "scout's code". 
6. Corrected some incorrectly written attributes within the html file. One such correction fixed the link to properly function.
7. Added comments to the css properties in order to defuse any confusion in the future.
8. Changed some css properties to make the page smoother. For example, elements "aside" and "section" had width total less than 100% in order to fit side by side.