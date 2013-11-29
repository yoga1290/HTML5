## apps.facebook.com/ [SubCover](http://apps.fb.me/subcover)

I was trying to upload Javascript generated/manipulated images to facebook and 1 day I was starting at someone’s profile picture photo which was a sub-image from the profile cover picture; later on, I tried writing some Javascript to do the same & that’s it
+	Mouse Click for popup,
Some browsers block popups if they weren’t triggered by some event; mouse click or smth
+	“Cross-origin resource sharing”,
Usually browsers will prevent Javascript (your script; your server) to load your profile cover, manipulate it and send it back to facebook; that’s why I’m passing images to my domain first then to the HTML5 page to be manipulated then to facebook via AJAX

