---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

# The Meteor Shower Begins

## The fiery rain of bugs
A common problem I ran into while developing the digits application has been my app crashing. This problem has definitely been a nuisance for me ever since we started have developing with meteor. I found that the most common error, for myself at least, was that I was missing a semi-colon or curly brace; I've also had times where I just forgot to close a div. As simple as these problems may be, one can spend quite a while searching for them, especially when they over think things. I like to think of these minor problems as a meteor shower, though not as spectacular as an actual meteor shower they can popo up as frequently as meteor in a meteor shower but as soon as you see them you say to yourself, WOW, and then they disappear. I solved this problem by doing a mental check, every time a tag was created, I made sure to include a closing tag before I even started to write anything else I planned to put in it. This new mental check has proved to be very valuable for me since I used to have a habit of putting things after a starting tag without firstly creating it's closing counterpart.

## Alignment? What's that?
Another very simple problem I have had and still to continue to see pop up is alignment. When creating a new page I type everything out and enthusiastically rush over to the browser to see my work only to be met with bad alignment and anything but an aesthetic look. I then proceed to go back into the code and find ways to properly align what I want to using css. As I said before this problem is still recurring. I've found temporary fixes, but nothing I would be completely satisfied with. My temporary solution is to put padding on a certain section I would like to try and center, the only problem with this solution is that it doesn't adjust to be centered when resizing the screen or when switching to a monitor with more or less pixels. I have also tried to incorporate the "auto" padding feature of css but I sometimes find it not working so I fallback to my padding solution.