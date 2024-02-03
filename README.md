# Clock-Animation

Clock Website
Welcome to the Clock Website! This simple web page displays an animated clock with rotating hour, minute, and second hands. You can use this code as a starting point or customize it to suit your needs.

##Preview

<h1>Features</h1>
1) Animated clock with rotating hands.<br>
2) Stylish design with a purple background.

HTML Structure (index.html)
Wrapper Container: <div class="wrapper"> - A container that encompasses the entire clock.

Clock Text: <ul id="clocktext"> - The heading text "CLOCK" displayed above the clock.

Clock Container: <ul id="clock"> - The main container for the clock, including numbers and clock hands.

Clock Numbers: <li class="numbers"><span>1</span></li> - Individual elements for each clock number (1 to 12).

Clock Hands: <li id="hour"></li>, <li id="minute"></li>, <li id="second"></li> - Elements representing the hour, minute, and second hands of the clock.

CSS Styles (watch.css)
Global Reset
*: Sets margin and padding to zero for all elements.
Wrapper Styles
.wrapper: Defines the overall layout of the clock, setting the background color, font-family, and size.
Clock Text Styles
#clocktext: Styles the heading "CLOCK" with background color, text color, font size, boldness, and shadow effects.
Clock Container Styles
#clock: Defines the appearance of the clock container, including its size, background color, border, and box shadow.
Clock Inner Circle
#clock:before: Adds a circular inner shadow to the clock container.
Clock Center
#clock:after: Creates a central circle within the clock.
Clock Numbers
.numbers: Styles the container for clock numbers, specifying position, size, and text alignment.
.numbers span: Styles each individual clock number, including color, font size, and text shadow.
Clock Hands Animation
#second, #minute, #hour: Configures the animation properties for the second, minute, and hour hands.
Clock Hands Styling
#second:after, #minute:after, #hour:after: Styles the appearance of the clock hands, including size, shape, color, and shadow.
Clock Hands Animation Keyframes
@keyframes sec: Defines the rotation animation for the second hand.

<h1>Getting Started</h1>
1) Clone the repository:

git clone https://github.com/your-username/clock-website.git

2) Open the index.html file in your preferred web browser.

<h1>Usage</h1>
Feel free to use this code as a template for your own projects. Customize the colors, styles, or add additional features to make it unique.

<h1>Styling</h1>
The clock styling is defined in the watch.css file. You can modify the styles to match your preferences or integrate it into your existing project. Feel free to explore and experiment with the code to create a unique clock design.

<h1>credits</h1>
Fonts: Josefin Sans
Icon: Icons8 Clock
