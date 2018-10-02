# 100 Days Of Code - Log

### Day 1: October 1st, 2018

#####

**Today's Progress:** Fixed some CSS on DrifterCode.com/kodefant.no, my bilingual Blog about web sites, communications and programming. I will from now on only call it DrifterCode since that is the English version. Both the Norwegian and English site is managed through the same WordPress install through the [WPML Plugin](https://wpml.org/).

DrifterCode is made with the Full [Roots Stack](https://roots.io/) including a Trellis server, the Bedrock boilerplate and the Sage 9 starter them with modern developer workflow like Webpack and Laravel Blade templating.

**Thoughts:** I initially made my Trellis install on a Mac several weeks ago, but wanted to continue developing it on my Ubuntu Linux machine. I pulled the code through the git repository and had some issues with some error messages about SSH and NFS. I managed to fix it, but it took a couple of hours to work out.

Battling configurations errors can test the patience of a guy just wanting to code. Still, all these tools are very powerful, open source and free, so I am very thankful. But when I google for fixes, I often end up on tutorials with lots of terminal commands. And some errors were because I configured my Linux installation with encryption on **/home**.

It sometimes feels like the need for all these guides signifies a bug that no one will claim. I think this applies to how the different technologies interact, so these things are probably not easy to solve for the developers. This must be challenging when working with DevOps, but I guess the DevOps engineers learn to live with these challenges.

Just to be clear, these tools are actually amazing, free and open source.

**Plans for tomorrow:** I want to start building a conceptual restaurant app. I think I will try building it with WordPress REST API and React on the Front End.

**Link to work:** [DrifterCode.com](https://driftercode.com), [kodeFant.no](https://kodefant.no) and [The Github repository](https://github.com/kodeFant/wp_kodefant)

### Day 2: October 2st, 2018

#####

**Today's Progress:** I decided to work on making the CSS Grids on my site [DrifterCode (eng)](https://driftercode.com)/[kodeFant (no)](https://kodefant.no) work on Internet Explorer 11. It was a dreadful, but I finally made it work on post-view and blog list. Lots of credit goes to this [CSS-Tricks and their series about Grid in IE](https://css-tricks.com/css-grid-in-ie-debunking-common-ie-grid-misconceptions/).

I chose to completely replace my auto-placement grid for Blog Posts with Flexbox as it did the excact same thing. I adapted the technique in part three of that CSS-Tricks series.


**Thoughts:** It was a big effort making the CSS grid work with IE11, even when using autoprefixer with their grid support enables. 

I want to support IE11 because about [10 percent of Norwegians use IE](http://gs.statcounter.com/browser-market-share/all/norway), and lots of them are in large organisations. I of course want to make a good impression on these organisations.

It's not fun adding support to IE11, but I think I learned something today that can be valuable in the time to come.

I have chosen not to add the Bootstrap to my website. It makes stuff including grid easyer, but I wanted to really improve my skills on CSS.

The upside to the hardships of today is that I found a fun CSS Grid Game: [Grid Garden](http://cssgridgarden.com/) :)

**Plans for tomorrow:** I discovered that my pages-view on DrifterCode.com displays really poorly on IE11, so I will continue on that before moving on to a new project.

**Link to work:** [DrifterCode.com](https://driftercode.com), [kodeFant.no](https://kodefant.no) and [The Github repository](https://github.com/kodeFant/wp_kodefant)

