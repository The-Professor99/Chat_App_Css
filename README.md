# Chat App Illustration with css - A [Frontend mentor](https://www.frontendmentor.io) challenge

This project aims to build a web page similar to the designs in the [design folder](./design).

You can check out my own work [here](https://upcomin.github.io/Chat_App_Css/#). I've also tried adding animations to make the solution more interesting.

##-Issues

In the input\[type="text"\] box, there's an animation for screen widths "(min-width: 480px) and (max-width: 559px)" and "(min-width: 768px)", upon hover of the animated element (the p.animate-me::after element), it's display is set to "none" so that the underlying text-box appears for text input, however, I feel this is not ideal cause after the hover, the animation restarts (but waits for the 18s delay set on it) whereas I want it to restart immediately after leaving the text-box. I can't seem to work around the issue, I tried adding "animation-play-state: paused; z-index: -1" but this causes a back and forth movement of the cursor (as the z-index pushes the element down thus releasing it from the hover so it comes up again to meet the cursor thus iterating over and over). "opacity: 0" isn't ideal either cause I want the text box reachable for text input. 

If there's a work around for this, please let me know...

###-Other Notes
As this is purely practice, I've not added support for older browsers nor have I added support for browsers which may not be compatible with some style rules(like --moz and -webkit-  style rules).

##Final Declaration

As I believe that we grow in the tech field everyday (even though the field grows faster than we do), it's my hope that you get to leave feedbacks ("drop something for the boy *winks*") as you pass through this repo, no matter how small it may be, I see it as necessary to the growth of one in this field and at the same time, an eye opener to concepts I may have been blinded to.

Your feedbacks will be very much appreciated.
