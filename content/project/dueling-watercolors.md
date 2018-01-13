---
title: "Dueling Watercolors"
date: 2018-01-13
draft: false
tags:
  - project
  - art
  - python
  - fun
---

Here is a fun little art project I made this morning!

I thought to myself "Self, what if we made a little program that would try to make 'watercolor-y' images by starting with a random canvas, and smudging the paint around?"

So I coded it up, and it looked cool, but not that cool:

<video controls>
<source src="/watercolors/averages.mp4" type='video/mp4'>
</video>

Then I thought "What if we made it so that it wasn't just poking the canvas randomly, but actually trying to match another image? That could be cool."

So I hooked the program up to a copy of itself, and got each copy to try to mimic the other:

<video controls>
<source src="/watercolors/small.mp4" type='video/mp4'>
</video>

There are a few rules:

 - The programs can only smudge the paint, not add or remove paint
 - The programs can't communicate, except by looking at each others' paintings
 - Each program has 24 smudges in its turn - they alternate turns
 - The canvas starts out randomly
 - They are only done when they both think there aren't any improvements to be made

So, under those constraints, how do you think the program did? If you are an artist (and have a friend), I challenge you to try it with real paint, and let me know how it goes.

<video controls>
<source src="/watercolors/movie.mp4" type='video/mp4'>
</video>

If you're interested in the source, it is [here](https://gist.github.com/setupminimal/a53a703e43d2f06fb62de4747c12b75c).

## Update later on 2018-01-13:

Due to popular demand (well, if one person and my boredom is popular), there is now a HTML5, phone-friendly paint-smudging game [called Smudge available here](/watercolors).
