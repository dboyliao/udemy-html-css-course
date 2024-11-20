# Course Material and FAQ for "Build Responsive Real-World Websites with HTML and CSS"

This repo contains starter files and final code for all sections and projects contained in the course.

Use starter code to start each section, and **final code to compare it with your own code whenever something doesn't work**!

👇 **_Please read the following Frequently Asked Questions (FAQ) carefully before starting the course_** 👇

## FAQ

### Q1: How do I download the files?

**A:** If you're new to GitHub and just want to download the entire code, hit the green button saying "Code", and then choose the "Download ZIP" option. If you can't see the button (on mobile), use [this link](https://github.com/jonasschmedtmann/html-css-course/archive/master.zip) instead.

### Q2: I'm stuck! Where do I get help?

**A:** Have you actually tried to fix the problem on your own? Have you compared your code to the final code? If you failed fixing your problem, please **post a detailed description of the problem to the Q&A area of that video over at Udemy**, along with a [codepen](https://codepen.io/pen/) containing your code. You will get help there.

### Q3: What VSCode theme are you using? What about extensions and settings?

**A:** I use [One Monokai](https://marketplace.visualstudio.com/items?itemName=azemoh.one-monokai) in this course. [Here is the complete VS Code setup for this course](vscode-setup.md).

### Q4: Can I see the final version of the Omnifood project?

**A:** Sure! Here you go: [Omnifood](https://www.omnifood.dev).

### Q5: Where can I find the coding challenge solutions?

**A:** They are all on codepen, in [this collection](https://codepen.io/collection/7b5e288cb64df1ecc5da8d7a0e78c007?grid_type=list).

### Q6: Where is the resources page you keep mentioning?

**A:** It's on my website at <https://codingheroes.io/resources>. You can subscribe for updates 😉

### Q7: Videos don't load, can you fix it?

**A:** Unfortunately, there is nothing I can do about it. The course is hosted on Udemy, and sometimes they have technical issues like this. Please just come back a bit later or [contact their support team](https://support.udemy.com/hc/en-us).

### Q8: Videos are blurred / have low quality, can you fix it?

**A:** Please open video settings and change the quality from 'Auto' to another value, for example 720p. If that doesn't help, please [contact the Udemy support team](https://support.udemy.com/hc/en-us).

### Q9: I want to put these projects in my portfolio. Is that allowed?

**A:** Absolutely! Just make sure you actually built them yourself by following the course, and that you understand what you did. What is **not allowed** is that you create your own course/videos/articles based on this course's content!

### Q10: I love your courses and want to get updates on new courses. How?

**A:** First, you can subscribe to my email list [at my website](http://codingheroes.io/resources). Plus, I make important announcements on twitter [@jonasschmedtman](https://twitter.com/jonasschmedtman), so you should definitely follow me there 🔥

### Q11: How do I get my certificate of completion?

**A:** A certificate of completion is provided by Udemy after you complete 100% of the course. After completing the course, just click on the "Your progress" indicator in the top right-hand corner of the course page. If you want to change your name on the certificate, please [contact the Udemy support team](https://support.udemy.com/hc/en-us).

### Q12: Can you add subtitles in my language?

**A:** No. I provide professional English captions, but Udemy is responsible for subtitles in all other languages (automatic translations). So please [contact the Udemy support team](https://support.udemy.com/hc/en-us) to request your own language.

### Q13: Do you accept pull requests?

**A:** No, for the simple reason that I want this repository to contain the _exact_ same code that is shown in the videos. However, please feel free to add an issue if you found one.

# Notes

## Box Model
- content: the content of the html element, text, images, etc
- padding: transparent area around the content, inside the border
- border: goes around the padding and the content
- margin: transparent area around the border, outside the border
  - we normally use margin to **create space between elements**
  - collapsing margin: when two margins touch each other, they collapse into one margin
    - the margin will be the size of the larger margin
    - this is a feature of CSS
    - it does not happen with padding or border
- There are two kind of elements in the box model: block and inline
  - block elements: elements that always start on a new line and take up the full width available
    - ex: div, h1, p, form, etc
    - by default, block elements have a width of 100%
  - inline elements: elements that do not start on a new line and only take up as much width as necessary
    - ex: span, a, img, etc
    - width and height properties have no effect on inline elements
    - padding, margin, and border properties can be applied to inline elements (only horizontally)
    - `display: block;` can make an inline element be rendered as a block element
  - `display: inline-block;`: looks like inline from outside, behave like block element on the inside
    - it won't create line breaks
    - it takes up only as much width as necessary for the content
    - all box model properties can be applied to inline-block elements
    - an `<img>` element is by default an inline-block element

# Useful Links
- https://jonas.io/resources/
- W3C page for pseudo classes: https://www.w3schools.com/css/css_pseudo_classes.asp
    - the n-th child pseudo class: it selects the elements that are the n-th child of their parent and that match a certain type of selector
      - ex: 'artical p:first-child' does not select the first p element in the article element, but the p element that is the first child of a article element
    - it's perfect to apply to the child elements that are of the same type
- https://www.youtube.com/watch?v=uFXweZepi1o&list=PLqivELodHt3iF_Spzdz_6LsOSPOyfDx-R
- HTML validator: https://validator.w3.org/
