
Create an html web app using HTML, Java script, and CSS.  This app will have the workflow referenced below.  This app will have 2 functions see details below.  All web app code must be annotated with very details comments easily understood by humans.  ensure the Matrix effect and the Banner effect are correctly implemented and don't interfere with each other

APP Workflow:
1.  Run the Load function for its stated duration.
2.  Run the Banner function for its stated duration.
3.  The app should then redirect the webpage to https://DOMAIN.COM
 
Function Details:
1.  The first function will be called Load, and will display a matrix style falling green text display called MAT.  See below for load function requirements.
2.  The second function will be called Banner, and will display a pulsating red String that says 64BITROBOT.COM.  See below for banner function requirements

LOAD FUNCTION REQUIREMENTS:
A.  The Load function will display a matrix style falling green text display called MAT
B.  The MAT should fade in at the start
B.  The MAT's vertical columns text data MUST start falling at random times.
C.  The MAT's text should be green, and the size MUST be 12.
D.  The MAT's display should be 100% of the height and width of the screen.
E.  The MAT's display should continue for 10 seconds.
F.  The Load function should then fade out the MAT, and turn the screen black for 1 seconds.
G.  The Load function should then release all data used to create the MAT in the browser cache, so that it does not build up in the browser cache.


BANNER FUNCTION REQUIREMENTS:
A.  The Banner function will display a pulsating red String that says DOMAIN.COM, and will be called the BAN.
B.  The Banner function should fade in the BAN, and run it for 5 seconds.
C.  The BAN's text MUST be red, and the size MUST be 12.
D.  The BAN's text should stay the same size while pulsating.
E.  The BAN's pulsating should be accomplished by making the red color brighter and darker to simulate the pulsation.
F.  The Banner function should fade in the BAN, and run it for 5 seconds.
G.  The Banner function should then fade out the BAN, and turn the screen black for 1 seconds.
H.  The Banner function should then release all data used to create the BAN in the browser cache, so that it does not build up in the browser cache.