# NYT Article Assignment

This is a project from The Odin Project entitled "Positioning and Floating Elements" - more details on the assignment [here](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/html-and-css/lessons/positioning-and-floating-elements).

The goal is to use any of the HTML and CSS methods I've learned so far to recreate the layout and design of this [New York Times article](https://www.nytimes.com/2014/03/18/science/space/detection-of-waves-in-space-buttresses-landmark-theory-of-big-bang.html?_r=0) (paywall warning).

We've learned all about the block model and using auto margins to center elements, how to use inline-block, floating content, etc. BUT we also learned about CSS Flexbox and Grid. Flex and Grid seem like the more modern approach, so I'll be using those.

In the assignment, they suggest using a combination of flex elements and block elements. I think what they wanted was for me to use `float: right;` on the little floating sidebar content. I quickly discovered that flex items don't work with the float property. It's probably not a best practice, but since I had already laid out the structure of my page, I just set the sidebar to `position: absolute;` and stuck it on the right-hand side rather than rearrange the whole page.