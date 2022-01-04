# Overview

This website is ideal for anyone looking for information about mindfulness, meditation and yoga, providing value information clearly explained with a very nice and cleaned design making it looks joyful, searching for an enjoyable user experience.

Displays clearly what the site is about, and what the user can expect, such as how to get started on any of the subjects, techniques, exercises, videos, podcasts meditation sessions, support, and so on and forth.

![](assets/images/responsiveness-devices.png)

* [Go to the live website](https://javierbl89.github.io/Mindfulness-Portfolio-Project-Code-Institute/)

## What you must know

At the moment all the links on the home page header and footer links on every page are desabled or will lead to the home page, as well as the hamburguer menu on tablet and mobile screen size will not expand.

To get into the main pages the user must clink on the button "LET'S GET INTO IT", which is clearly displayed in the mid of the home page.

All the content has been copied and pasted away, only been carefully chosen from differents sources, as well as videos, nothing it's been taken ligthly.

# Table contents

### [Planning stage](#planning-stage)

  - Target Audiences
  - User stories
  - Design goals
  - Design choises
  - Font
  - Color scheme
  - Wireframes

### [Features](#features)

  - Descriptions
  - Exercises
  - Videos
  - Shop
  - Support
  - Navigation
  - Page links navigation
  - Collapse menu

### [Future features](#future-features)


## Project images

Desktop
[](assets/images/Captura%20de%20pantalla%20(25).png)
[](assets/images/Captura%20de%20pantalla%20(26).png)
[](assets/images/Captura%20de%20pantalla%20(27).png)

Mobile
[](assets/images/Captura%20de%20pantalla%20(30).png)
[](assets/images/Captura%20de%20pantalla%20(31).png)
[](assets/images/Captura%20de%20pantalla%20(32).png)

# Me
I'm only new to programming. Last year i took up a Full Stack Web Development course through Udemy tought by Angela Yu, which is a well-rounded and extense course.

After building up a few walk through projects, i am happily putting out there my very first project on my own.

I chose one of the Projects ideas provided by Code Institute, since I'm not very agil for now to come up with apps ideas.. :)

Following the Portfolio 1 Code Institute Project rules, this project is build-up by only using HTML and CSS, so you'll find the burhuer menu no functional, although i implemented Boostrap for Navbar layout and for buttons style in cases i needed it.


# Project Estructure

The project is divided in 6 pages:

### Main pages
1. HOME
https://javierbl89.github.io/Mindfulness-Portfolio-Project-Code-Institute/index.html

2. MINDFULNESS
https://javierbl89.github.io/Mindfulness-Portfolio-Project-Code-Institute/assets/html/mindfulness.html

3. MINDFULNESS MEDITATION
https://javierbl89.github.io/Mindfulness-Portfolio-Project-Code-Institute/assets/html/mindfulness&meditation.html

4. MEDITATION
https://javierbl89.github.io/Mindfulness-Portfolio-Project-Code-Institute/assets/html/meditation.html

5. YOGA
https://javierbl89.github.io/Mindfulness-Portfolio-Project-Code-Institute/assets/html/yoga.html

### Sub pages
6. BODY SCAN
https://javierbl89.github.io/Mindfulness-Portfolio-Project-Code-Institute/assets/html/bodyScan.html

# Pages structure

Every page is made up by;

1. Navbar.
2.Navigation bar for external pages.
3.Navigation bar for page sections.
4.Page content.
5.Footer.

# CSS files structure

I have reused plenty of code for templaiting, and i have organised the CSS code for it to be easy to find by using the line numbers as landmarks, so all of the CSS files(except home.css) are equally structure:

Line 1 onwards    -Common Features.

Line 180 onwards  -Page content for Desktop.

Line 325 onwards   -Media 1000px Common Features.

Line 480 onwads    -Media 1000px Page Content.

Line 580 onwards   -Media 575px Common Features.

Line 740 onwards   -Media 575px Page Content.


# Developing the project

Plenty of features could be added such as;

1. Sing in page.
2. User page.
3. Guided exercises according to levels.
4. Weekly/Monthly Guided exercises for the ones with little spare time or the ones who need some guidance to tel them what to do next, etc.
5. Payment page.
6. Related content, such as videos, interviews, books, gear.. etc.
7. Community, set up a community interface for sharing, helping, meetings and live meditations sessions.
8. Shop linked to the page.

# Bugs

Sometimes i can't seem to target the css elements from the external CSS file... i don't know why it happens..

Also even reusing the code, it seems to behave differently in some page... i don't get why...
For instance the navigation bar for external pages(i don't know whether if i'm saying that right), mean the navigation bar for MINDFULNESS MINDFULNESS/MEDITATION YOGA MEDITATION pages, with that one have came across with a layout issue on the mobile size in only the MINDFULNESS and YOGA pages. Where it says mindfulnes meditation, the words woul go onto each other changing the layout, like this:  ![](../images/Captura%20de%20pantalla%20(24).png)

The odd thing is that it only happen in the Mindfulness page.

To solve this, i didn't want to change the font size as it would be too small to my liking, so i wided its container margin and did the same in all the pages to make sure it does not happen in any device to any page.

Another challenge was to figure out the files paths when deploying into github, i have spent quite a few hours of trail an error, till i realized github needs a few minutes to finally update changes..

That's all for, see you soon!
