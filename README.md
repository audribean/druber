# Druber Demo

Welcome to Druber! It's a bit scrappy, but it shows my thought-process when approaching mobile design.

I first had to make a plan before doing any refactoring. I started by identifying groups of elements and determining whether they should remain side-by-side or wrap into a single column. The header, for example, is a group consisting of the name and tagline, and a textbox. Since an interactive component like a textbox would would be best with maximum width on a smaller screen, this section turned into a long column. 

I worked out a general plan for both kinds of screens in Figma, which can be seen [here](https://www.figma.com/file/TKRExFTaQvHtIre9fB8fwM/Untitled?node-id=3%3A5). 

After planning what would change, I linked the W3.CSS and W3.CSS pro frameworks (simple frameworks for a simple page), and tinkered section by section (I had divided these into top, middle, and bottom). The framework takes care of response to fluid changes to the window size like text justification and the row/column displays for elements I mark. I also made sure to use relative size units like vw and %. For other changes, I used media queries. They're convenient, because I had already structured the page using flexboxes and could modify select attributes according to what would look best. My favourite use of them was changing the background image from one that's horizontally dynamic to one that's vertically dynamic when the screen is narrow. Then I added extra changes to fix clashing elements or anything that got unaligned -- this part could still use work.

There were some other changes to consider for mobile as well, like a side menu that could make navigating the website easier and eliminating side margins on images with the bottom section. I had set out of a plan for this (outlined in my comments and figma doc), but my time to work on this demo got cut short after getting Covid this week. 