#Show me the slides

An overview of the slides available form this repository can be viewed [here](http://pythonslides.review) or [here](http://pythonslides.netlify.com).

#Background

When researching for my first offering of a programming course at IIT Gandhinagar, I was quickly overwhelmed by (and also grateful for) all the [great resources](/resources/) that I could find to learn Python. As it turned out, I was in a situation where the classes were held in a non-lab environment (i.e: no computers). I considered the possibility of making every class a live coding session, and potentially recording screencasts to share with the class.

However, after watching the the lectures from the  [NPTEL course on Programming, Data Structures and Algorithms in Python](https://onlinecourses.nptel.ac.in/noc16_cs11/preview), I realized that creating slides was perhaps a more organized way of delivering the material. I should note that the organization of the material in these slides is inspired by this and other courses, which are listed on the [resources](/resources/) page.

I explored the possibilities of using [Pythontutor](http://pythontutor.com) and embedding REPLs from [REPL.it](http://repl.it) in the class. Given that I wanted to incorporate these into my slides, it was natural for my to explore JavaScript-based frameworks for making slides. I finally settled on [remarkjs](http://remarkjs.com), which turned out to be just right for my needs: the slides look qutie nice out of the box, there is some support for incremental slides, syntax highlighting (via highlightjs) and LaTeX (via Mathjax), the content of the slides can be written in a reasonable flavor of markdown^[see Yihui Xie's [post](https://yihui.name/en/2017/08/why-xaringan-remark-js/) for more remarks on this], and presenter notes. Because it skips some of the bells and whistles, it was also easy for me to get going with.

My original set of slides for the class were written directly in HTML using Remark. For the current version, I am using the xaringan package mostly because of the easy live preview functionality (although there are other ways of getting live preview to work) and my hope that I will eventually take advantage of having xaringan execute the Python blocks in the slides will come in handy --- which I think is the [main distinction](https://slides.yihui.name/xaringan/#15). Considering there is almost no extra work compared to using Remark directly, I decided to make the switch even though all the output examples in the slides at the time of this writing are/were generated manually.

#Usage

Do feel free to use these slides directly if you find them useful - you can simply access them via the links on the website [here](http://pythonslides.review) or [here](http://pythonslides.netlify.com) (remember to use the `F` key to run them in fullscreen mode). You could also fork this project or download the files and use them as a baseline for your own customized decks. I would also look forward to any contributions in terms of corrections or additional content.
