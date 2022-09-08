# assignment2-Nagadesi
Hello I'm Charita. I got familiar with Git and its commands.

# N D Thanmai Charita
###### My favourite museum to visit is Museum of modern Art.

The Museum of modern at New York is famous for its **vast collection of arts**.It plays a major role in developing and collecting modern art, and is often identified as one of the **largest and most influential museums** of modern art in the world.

---

# Directions from airport to museum
1. The nearest airport to yhe museum is JFK International Airport.(New York)
2. JFK Airport to museum.
    1. Complete your check in process in Airport.
    2. Book a cab
    3. Wait for your driver until he arrives
    4. Board the cab and go to museum.

* Time square
* Statue of Liberty
* Brooklyn Bridge
* Empire State Building

[Click here for AboutMe](https://github.com/tanmaycharita/assignment2-Nagadesi/blob/main/AboutMe.md)

---

# Cities that I would like to recommend others

I like visiting new places and I travel alot. I am passionate about photography and I like clicking pictures of places that I visit everytime. So, below are the few places that I would suggest others. Enjoy!!

| City name                         | Location       | Price |
| ---                               | ---            | ---:  |
| New York                          | Time Square    | $120  |
| Chicago                           | Sky deck       | $75   |
| Seattle                           | Space Needle   | $80   |
| Los Angeles                       | Disneyland     | $250  |

---

# Quotes

> " Whatever you are, be a good one."
>      - by *Abraham Lincoln*
>      
> "What is life, without a little Risk."
>      - by *J.K. Rowling*

---

# SVG Patterns

> Animating an SVG pattern background
>
> I'm currently designing a new website with NextJS and Tailwind and I would like to make a background that is infinitely translating to the bottom right, just like in this example (but with my own pattern):

Question link - <https://stackoverflow.com/questions/67848272/animating-an-svg-pattern-background>

```
<svg width="100%" height="100%">
  
  <!-- Create mask that we'll use to define a slight gradient -->
  <mask maskUnits="userSpaceOnUse" id="fade">
    <!-- Here's that slight gradient -->
     	<linearGradient id="gradient" x1="0" y1="0" x2="0" y2="100%">
      <stop offset="0" style="stop-color: #FFFFFF"></stop>
      <stop offset="1" style="stop-color: #000000"></stop>
    </linearGradient>
    <!-- The canvas for our mask -->
    <rect fill="url(#gradient)" width="100%" height="100%"></rect>
  </mask>
    
  <!-- Let's define the pattern -->
  <!-- The width and height should be double the circle radius we plan to use -->
  <pattern id="pattern-circles" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
    <!-- Now let's draw the circle -->
    <!-- We're going to define the `fill` in the CSS for flexible use -->
    <circle mask="url(#fade)" cx="20" cy="20" r="20"></circle>
  </pattern>
  <!-- The canvas with our applied pattern -->
  <rect x="0" y="0" width="100%" height="100%" fill="url(#pattern-circles)"></rect>
  
</svg>
```

Source link - <https://css-tricks.com/snippets/svg/svg-patterns/>

