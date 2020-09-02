# Skim of Chapter 10
I took the Code 101 course, so this chapter was a bit of review. The key thing to remember about a CSS file is that it is used to standardize customizations of web pages on a site in a _one stop shop_ type of way. That is, rather than having to set each image height and width in the site, you can create a class in the CSS file, and then reference that class anywhere you want in your site and it will use the height and width found in the CSS file. It is important to remember to link the CSS file in the < head > section of each page so that page knows where to get the information from.

If you want, you can also define CSS per page rather than using a file. This is not the recommended method has if you make a change to the CSS you would have to do it on each page rather than once in the CSS file.

CSS rules cascade. This means that if two classes share the same name, the later of the two will be used. Also, if one class is named differently, but more specific than the previous one, the more specific will be used. So, p#intro is more specific then p.

Also, CSS childern classes can inherit settings from a parent class. So, if body has some setting, and .page is a child of body it can inherit, or use, settings from the parent while changing the settings that need to be changed.

# Chapter 11
Chapter 11 deals with color and how to set color on a web page.

There are two types of colors: color and background-color. Color sets the font color, which background-color sets the background of the area/page.

There are four different ways to set the color:
1. **rgb** or **rgba** - use the rgb(XXX,XXX,XXX) to set the color, rgba adds in the option of setting opacity to the color. use rgb(XXX, XXX, XXX, X.XX)
   - the first number is for _red_. It needs to be a number between 0 and 255
   - the second number is for _green_. It needs to be a number between 0 and 255
   - the third number is for _blue_. It needs to be a number between 0 and 255
   - when using rgba, the a is a number between 0 and 1. The closer to one the higher the opacity level is set.
   - for the color medium aquamarine you would enter rgb(102, 205, 170)
2. **hex** - use #XXXXXX to set the color 
   - the first set of two numbers set the _red_. This is in hexadecimal, so the value must be between 00 and ff, and must include both numbers
   - the second set of two numbers set the _green_. This is in hexadecimal, so the value must be between 00 and ff, and must include both numbers
   - the third set of two numbers set the _blue_. This is in hexadecimal, so the value must be between 00 and ff, and must include both numbers
   - for the color medium aquamarine you would enter #66cdaa
3. **by name** - use a defined name to set the color
   - you could enter the name MediumAquaMarine to set the color
   - there are 147 defined names at this time
   - One site that lists them [is this one](https://htmlcolorcodes.com/color-names/)
4. **hsl** or **hsla** - sets the _hue_, _saturation_, _lightness_ and when the a is used the _alpha_
   - hue is represented by all the colors in a circle. The number used is what degree around the circle the color is located
   - saturation is a percent from 0 to 100 to add a shade of gray to the hue
   - lightness is a percent from 0 to 100 to represent how much black, 0%, or white, 100%, is used. 50% is "normal"
   - when used, the alpha represents the transparency  of the color. This is a number between 0 and 1. 0.5 would represent 50% transparency
   - for the color medium aquamarine you would enter hsl(160, 51%, 60%) and if you wanted it to be partially transparent, hsla(160, 51%, 60%, 0.5)
   
When using color, one must be carful and watch for **contrast**, or how difficult it is to read/see something. So, a light color on a light background-color may be difficult to read.
