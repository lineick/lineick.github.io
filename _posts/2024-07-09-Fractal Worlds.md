---
title: Fractal Worlds
date: 2024-07-09 22:37 +0200
categories: [Math, Philosophy]
tags: [fractals, math, philosophy, art]     # TAG names should always be lowercase

media_subpath: /assets/post_content/fractals/

pin: true
math: true

image:
  path: simple_fractal.jpeg
  alt: compressible beauty
---

> A fractal is a curve or geometrical figure, each part of which has the same statistical character as the whole
{: .prompt-info }

I was always fascinated by complex structures emerging over simple rules.
It is as visualizing the fractal patterns behind simple formulas reveals already existing worlds, embedded and hidden in the maths, waiting to be revealed, and spoiler sometimes looking shockingly close to known structures.
In school I stumbled over the Youtube channel [Numberphile](https://www.youtube.com/@numberphile), which presented some really interesting math concepts, including fractals which fascinated me right away.
My simplest intuitive definition is that *it is a recursive pattern*, so it has infinite intricacy while zooming in, revealing its repetitive patterns.
Because they can be defined recursively, their complexity is perfectly compressible into (mostly simple) rules.

One of the most prominent and fascinating instances is the Mandelbrot Fractal and its related fractals, such as [Julia sets](), [Multibrot sets](), the [Burning Ship Fractal]() and my favorite: the [Bhuddabrot]() and its RGB version the Nebulabrot.
And no it has to do with the german word brot (bread), it is named after its discoverer, the mathematician [Benoit Mandelbrot](https://en.wikipedia.org/wiki/Beno%C3%AEt_Mandelbrot).

## But why is the Mandelbrot Fractal so cool?

The mandelbrot set is simply defined as the set of complex numbers $$ c\in \mathbb{C} $$ for which the sequence $$  z_{n+1}=z_n^2 + c $$, starting at $$ z_0 = 0 $$ is bounded.
For visualization we simply graph each $$ c $$ as a 2D point (real part on x-axis, imaginary part on y). The points of the Mandelbrot set are simply colored black.
However the magic happens when plotting the divergence of the sequence at the borders of the set. Given a color scale, we simply relate the speed of divergence for each $$ c $$ to a color.
Thats it...

{% include embed/youtube.html id='b005iHf8Z3g' %}
*Zooming into the mandelbrot fractal*

It is fascinating how this simple formula reproduces such intricate new worlds when plotted in such a way. Makes one think if our own universe is a fractal (I will come back to that at the end).
Althogh infinitely repeating, there are many iconic substructures in the mandelbrot fractal, such as the elephant valley or the *seahorse valley*, located in the region between the left and right big bulb:

![Seahorse Valley](seahorse.jpg)
_seahorse valley, one of the iconic substructures in the Mandelbrot fractal_

So far we only mapped the different $$ c $$ values of the sequence to the pixels. If we instead keep $$ c $$ constant and map the $$ z_0 $$ values to each pixel, we obtain the related Julia fractals and sets for each point in the mandelbrot fractal, which themselves are subpatterns in the mandelbrot fractal.

{% include embed/youtube.html id='FFftmWSzgmk?start=925' %}

There are many more hidden connections in the mandelbrot set, such as $$ \pi $$ hiding in scaling properties of its self-similar structures and external angles in the complex plane, but this would be far to technical for this post ([Pi in the mandelbrot set](https://www.doc.ic.ac.uk/~jb/teaching/jmc/pi-in-mandelbrot.pdf)).

## My favorite: The Bhuddabrot

- present the bhuddabrot, nebulabrot and mapping between both
- Close with some other cool fractal sets and its 3D version.

- Fractals in nature, snowflakes, shells (video) => simple rules, easy to build for self organizing structures
- Philosophy: The universe as a fractal, simple rules being used over and over again. (Compressible => perfect prediction possible??)


The RGB Version of the Bhuddabrot (Called [Nebulabrot](https://en.wikipedia.org/wiki/Buddhabrot)):

![Nebulabrot](nebulabrot.jpg){: w="700" .left .shadow }
_An Image of the Nebulabrot rendered by coloring each pixel based on its number of visits for escaping c values of the mandelbrot series ($$ z_{n+1}=z_n^2 + c $$ where $$ c \in \mathbb{C} $$ and $$ Z_0=c $$) in a given number of iterations (e.g. 2000 for red, 200 for green and 20 for blue)_

If you are interested, consider in some aestetic visualizations, check out this short [post](https://benedikt-bitterli.me/buddhabrot/)

Here is one of his 

For a simple and easy introduction check out this video by numberphile:


{% include embed/video.html src='bhudda_mandel.mp4' title='Rotating between Mandelbrot and Bhuddabrot' autoplay=true loop=true %}

> Credits to Benedikt Bitterli
{: .prompt-info }

## Random tests

This is how inline code looks like `print("Hello World")`. The following generates the sequence used to obtain the mandelbrot set (in set if seq is converging):

```python
def mandelbrot_seq(c, max):
  def seq(z_seq):
    if(len(z_seq)<max):
      z_seq.append(z[-1]^2+c)
    return seq(z_seq)

  return seq([c])
```


