README FILE

# Portfolio Website - Assignment 1

--------------------------------------------------------------------------------------
## Color Scheme
My website uses a dark theme with light gray tones for better readability.
- Header/Banner: #0d0d0d (almost black)
- Body Background: #2c2c2c (dark gray)
- Text: #f5f5f5 (soft white)
- Panels: #ffffff (white panel cards)
- Links/Buttons: #00bfa6 (Teal color for links and buttons)
- Hover Accent: #00e6c0 (Brighter teal when hovering over link or buttons)

Color scheme was picked and adjusted using Adobe Color (https://color.adobe.com/create)
---------------------------------------------------------------------------------------

----------------------------------------------------------------------------
## View Ports
My website uses three viewport stylesheets:
- mobile.css: for screens with (min-width: 600px). Picked this dimension because most phones have screens smaller or equal to 600px wide in portrait.  I made the navigation vertical with full-width inputs to make sure the text buttons are big so they're easier to click.

- tablet.css: for screens with (min-width: 601px) and (max-width: 900px). Tablets mainly fall into this dimension range, they are wider than phones but smaller than laptops so I put inline navigation and slightly larger layouts. 

- laptop.css: for screens with (min-width: 901px). Laptops and monitors are usually bigger or equal to 901px which is why I chose this dimension. I centered the main content and added max-width: 1000px to make sure the content doesn't stretch across the whole screen. 

- global.css: Has the shared base styles across every device.
----------------------------------------------------------------------------

----------------------------------------------------------------------------
## Gradients
Two types of gradients were used:
- Angled Gradient: The header banner uses an angled gradient. 
linear-gradient(135deg, #0d0d0d, #222222)
- Linear Gradient: Introduction section uses a linear gradient.
linear-gradient(to right, #0d0d0d, #222222)
----------------------------------------------------------------------------

## External Code References
Some code that I used was not in the lecture slides. They will be cited here.

1. Dynamic Year Footer
Code:
     html
   <script>
     document.getElementById('year').textContent = new Date().getFullYear();
   </script>
Source: https://developer.mozilla.org/enUS/docs/Web/JavaScript/Reference/Global_Objects/Date
Function: Automatically shows the year in the footer by filling it inside the span.

2. CSS Reset
Code:
html, body {
  margin: 0;
  padding: 0;
}
Source: https://www.w3schools.com/css/css_howto.asp
Function: Removes the default browser spacing for a more consistent layout.


