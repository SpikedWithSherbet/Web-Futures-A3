# <a name="_976xo7219f03"></a>**Front-End Web Design - Web Futures Reflection**

Disclaimers:

- I reccomend you use Google Chrome for viewing this for full compatibility.

- I am unsure how the Spline viewer will run on lower-performing systems. I have made a branch of the website on the GitHub page without the Spline viewer for marking purposes.

## <a name="_18thnmo2mtpf"></a>Design Inspirations

I first started with taking design inspirations from Aesop’s Fables for this project. I had recently picked up and read through them from Word Cloud Classics, and it inspired me to make a website based on the animals depicted, as well as greek colours and architecture, with a modern spin.

There also weren't many modern websites that depicted Aesop’s Fables. This was my chance to try something new.

## <a name="_f6pqspueu31z"></a>Use of AI

[Full ChatGPT conversation](https://chat.openai.com/share/6376d1ea-af91-4bdc-8e52-98112f725145)

I was very delicate with how I used AI in this project. The grounds for which was that AI-scripted code is unreliable, unsourced, and does not consider optimisation or accessibility. Instead, I utilised ChatGPT for some layout elements, sections of the website, colour palette, and typography. Instead of using any code given, I decided to follow and edit some of the guidelines given as if it were a design brief from a client.

What I used for the website from the conversation was:

- “Incorporate images or illustrations of  key characters from Aesop’s Fables”
- “Use subtle animations or hover effects to make navigation engaging.”
- “Each fable should have its own page with a unique layout.”
- “Use a clean and readable font for the text, with a colour scheme inspired by ancient Greek pottery or art.”
- “Dedicate a section of the website to profiles of characters from Aesop's Fables.”
- “Include illustrations or animations of each character along with a brief description of their role in the fables.”
- “Ensure that the website is fully responsive and optimised for mobile devices, as many users will access it on smartphones or tablets.”
- Colours: Primary - Terracotta (#E2725B)  Secondary - Sandy Beige (#D2B48C), Text and Background - Creamy White (#F5F5F5)
- Fonts: Headings - EB Garamond, Medieval Sharp, Body - Lato, Morals - Dancing Script

The reason for limiting the use of AI as well is that it occasionally gives responses that make the website look ugly. Particularly with its colour palette and typography. I only used three colours out of the seven it gave me, as the others were too tacky or were sickening to look at. Some of the sections didn’t make sense for my scope either; there isn’t too much to write about in a ‘blog’ section of the website, for example. Overall, there needs to be human intervention for a website to be well-scripted and visually appealing. 


## <a name="_j5v6ijoh9b0"></a>New Technology

One aspect that AI still does not do is innovate on web trends. This is why I decided to add the new features and aspects as discussed below, with appropriate references.

### <a name="_20ys5erjqaw9"></a>3D Diorama Integration and Spline

First, I found the new trend and software spline by watching this video: [Top 2024 Web Design Trends](https://www.youtube.com/watch?v=qthkkHPNAYQ&t=110s)

I had never seen 3D be used to a large extent in a website before; and I also wanted to expand my skill with the Voxel (3D Pixel) software MagicaVoxel. I thought this would work well as the “hero image” of the page, as it would be more appealing and dynamic. Lastly, it fulfilled the requirement of using illustrations of animals in the site. I used MagicaVoxel for the Spline diorama, as well as the fable thumbnails. 

My issue with this aspect, however, is I had to be very careful with using it in terms of computer performance. For this reason, I used a live viewer only for the hero image, and the rest I just captured as an image externally. 
### <a name="_qxd0pu6gwwfd"></a>Typewriter Headings

Sourced from [CSS Tricks Typewriter Effect](https://css-tricks.com/snippets/css/typewriter-effect/)

I wanted to give a “writing a story” feel to the fable headings, so I used a typewriter animation for them.

It does have the issue of hiding the text on lower resolutions, so I had to turn it off for mobile screens.

### <a name="_bw623blboutk"></a>CSS-Only Pop-Ups

Sourced from [What’s New in CSS and I/O 2023 Popover](https://developer.chrome.com/blog/whats-new-css-ui-2023#popover)

I wanted to add popovers to the Cast section to make the items feel convenient and streamlined, not needing to navigate to a different page for the information. Earlier, this would’ve taken some JavaScript functionality. Luckily, adding CSS-only popovers helped make it a reality without the headache of using JavaScript. I used these to provide short information on some of the characters, as the AI prompt provided.

### <a name="_68hqb90tcjn"></a>Fade-In Transitions

Sourced from [Incredible scroll-based animations with CSS-only](https://www.youtube.com/watch?v=UmzFk68Bwdk)

To make my website flow better, and to make it seem more visually appealing, I added fade-in transitions on the recommended fables section. I think this adds a sense of progression to my website. It also helps users categorise the grid together through the Gestalt Principle of Common Fate. 

I did make it only for those who had no preference for movement on the pages, to reduce motion sickness for some users (this was discussed in the source above)

### <a name="_2d68cdft110y"></a>Anchor Points

Sourced from [How to Add Smooth Scrolling Anchor Links to Jump to a Specific Part of a Web Page - HTML & CSS](https://www.youtube.com/watch?v=k4EGA95ZK4o)

To navigate to parts of the pages quicker, I used anchor points for the navigation section. This allowed for easy access to the other parts of the page from the topnav.

## <a name="_mx048jat01qo"></a>Considerations and Criticisms

- As this was a mock website, I have only added Lorem Ipsum for the body text.

- I didn’t want to add any extra fable pages, so I only added one as an example. I could’ve streamlined this process by using twig files.

- I used the [W3Schools template (Topnav, content, and footer)](https://www.w3schools.com/css/css_templates.asp) in the beginning for the base outline of my website. 

- I made the website responsive for smaller screen sizes. I made grids into single columns, and I also made the text smaller. For the main page, I did need to remove the Aesop illustration on smaller sizes to fit text.

- I wanted the cast icons to be smaller so that they resemble application icons. This was mainly to comply with responsive design. 

- Unfortunately, I had a difficulty with setting the margins properly for different displays. I have a few redundancies for headings, but they are required to re-adjust some margins to be in line.


- I have added alts for all images for accessibility purposes. 

- Overall, I am very proud of how the project turned out. It allowed me to use the culminated knowledge from past projects, understanding the use of AI, and expanding my repertoire of HTML and CSS technologies.



## <a name="_igczp8bqu8dq"></a>References

[Top 2024 Web Design Trends](https://www.youtube.com/watch?v=qthkkHPNAYQ&t=110s) - Codex Community on Youtube

[CSS Tricks Typewriter Effect](https://css-tricks.com/snippets/css/typewriter-effect/) - Geoff Graham on CSS Tricks

[What’s New in CSS and I/O 2023 Popover](https://developer.chrome.com/blog/whats-new-css-ui-2023#popover)

[Incredible scroll-based animations with CSS-only](https://www.youtube.com/watch?v=UmzFk68Bwdk) - Kevin Powell on Youtube

[How to Add Smooth Scrolling Anchor Links to Jump to a Specific Part of a Web Page - HTML & CSS](https://www.youtube.com/watch?v=k4EGA95ZK4o) - Web Dev Tutorials on Youtube

Turtle, Lion, Rabbit Icons - <https://icons8.com/>

Wolf Icon made by PLANBSTUDIO on FlatIcon - <https://www.flaticon.com/free-icon/wolf_8531941?term=wolf&page=1&position=4&origin=search&related_id=8531941>

Aesop Illustration - Public Domain

Aesop. (2013). Aesop’s Fables (V. Jones, Trans.). Printer’s Row Publishing Group. (Original work published 620 B.C.E.)



