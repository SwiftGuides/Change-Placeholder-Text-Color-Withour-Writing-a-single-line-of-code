# Change-Placeholder-Text-Color-Withour-Writing-a-single-line-of-code
This Trick is to change textfield placeholder textcolor without writing a single line of code 


Source :- https://stackoverflow.com/a/32245487/10422074

#Steps

You can accomplish this quickly, without adding a line of code, using Interface Builder.

1. Select the UITextField and open the identity inspector on the right

![alt text](https://i.stack.imgur.com/3K0tn.png)

2. Click on the plus button and add a new runtime attribute:
 
 ```
 placeholderLabel.textColor (Swift 4)

_placeholderLabel.textColor (Swift 3 or less) 

```


3. Use Color as type and select the color.

That's it!

You wont see the result until you run your app again.
