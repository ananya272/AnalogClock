# AnalogClock
Creating an analog clock using HTML, CSS, and JavaScript involves designing the clock face with HTML, styling it with CSS, and then using JavaScript to animate the clock hands.

HTML: 
We create a div with the class clock and three child divs with classes hand, hour, minute, and second. Each of these represents the hands of the clock. We also add a div with the class center to represent the center of the clock.

CSS:
We style the body to center the clock on the page.
The .clock class gives the clock a circular shape and applies some styling to make it look nice.
The .hand class styles the clock hands and positions them at the center of the clock.
Additional classes for .hour, .minute, and .second define different widths and colors for the clock hands.
The .center class styles the small circle at the center of the clock.

JavaScript:
The setClock function calculates the current time and sets the rotation for each clock hand based on the current hour, minute, and second.
The setRotation function applies the rotation to the clock hands using CSS transforms.
setInterval is used to update the clock every second.
This code will create a functional analog clock that updates every second to show the current time.
