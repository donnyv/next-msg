# next-msg
If you’re tired of over engineered tooltips, then this is for you, clean and simple.

````javascript
$("#btSubmit").nextMsg({ msg:"Tool-tip text goes here", CSSClass: "nextMsg-DarkTheme" });
````

This jQuery plugin creates popup tooltip messages next to the selected element. All theming is controlled using css, no images are used! Included in the zip is a demo and some screenshots.

## Browser Support
IE 7+, Google Chrome, Firefox, Safari, Opera 

## Themes
The css provides some canned themes that you can use. But you can always make your own. 
![Alt text](http://i.stack.imgur.com/Tjeh4.jpg?raw=true)

````
$.fn.nextMsg.defaults = {
                
                msg: "",
                // Message that will go in the box. 
                // Also accepts html
                
                side: "rightMiddle", 
                // Set which side you want the tooltip to appear. Defaults to "rightMiddle".
                // options: leftMiddle, topMiddle, rightMiddle, bottomMiddle
                
                CSSClass: "",
                // Name of the css theme class to apply
                
                maxWidth: 0,
                // This will let the message box expand the width up too the set maxWidth. It uses the css max-width property.
                
                width: 0,
                // Sets the width of the message box. Setting this property will override the "maxWidth" property.
                
                fadeSpeed: 500,
                // Used for the fadeIn and fadeOut speed
                
                displayDurationPerCharacter: 125,
                // This is used to calculate how long the message should be shown depending on how long the message text is.
                
                minDuration: 2500
                // Makes sure that message is shown for at least this amount of time
                // If you set it to -1 it will show until you click on it.
    };
````
