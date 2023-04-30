#  DIY (Do-It-Yourself) - Yes, You Can! Design Your Own Punks Using the Punk (Building) Blocks

Use the [free ImageMagick tools](https://imagemagick.org)
to make your own punks.



### Alien with Cap Forward, Small Shades & Pipe

Let's make punk #7804 - a super rare alien
![](https://github.com/openpunkart/punks.blocks/raw/master/basic/alien-male.png)
with a capforward
![](https://github.com/openpunkart/punks.blocks/raw/master/basic/m/capforward.png),
smallshades
![](https://github.com/openpunkart/punks.blocks/raw/master/basic/m/smallshades.png)
and a pipe
![](https://github.com/openpunkart/punks.blocks/raw/master/basic/m/pipe.png)
from scratch:

```
$ magick convert alien-male.png \
                 capforward.png \
                 smallshades.png \
                 pipe.png \
         -background none -flatten punk7804.png
```

<!--
$ magick convert alien-male.png capforward.png smallshades.png pipe.png -background none -flatten punk7804.png
-->

Now open up the new `punk7804.png`. Enjoy your million-dollar punk look-a-alike. Yes, it's
a 100% true authentic pixel ~~copy~~ original.

![](i/punk7804.png)



Zooming In - 2x, 4x


Scale up the image by doubling the pixels (that is, use the `-filter point` option).
Let's try 2x (that is, 200%):

```
$ magick convert punk7804.png \
         -filter point -resize 200% punk7804@2x.png
```

<!--
$ magick convert punk7804.png -filter point -resize 200% punk7804x2.png
 -->

![](i/punk7804@2x.png)

And 4x (that is, 400%):

```
$ magick convert punk7804.png \
         -filter point -resize 400% punk7804@4x.png
```

![](i/punk7804@4x.png)

<!--
$ magick convert punk7804.png -filter point -resize 400% punk7804x4.png
 -->


Why stop? Let's add a smile ![](https://github.com/openpunkart/punks.blocks/raw/master/misc/smile-alien.png)!

```
$ magick convert punk7804.png \
                 smile-alien.png \
         -background none -flatten punk7804_smile.png
```

<!--
$ magick convert punk7804.png smile-alien.png  -background none -flatten punk7804_smile.png
-->

![](i/punk7804_smile.png)   2x, 4x:
![](i/punk7804_smile@2x.png)
![](i/punk7804_smile@4x.png)


Try the natural version ![](https://github.com/openpunkart/punks.blocks/raw/master/natural/alien-male-natural.png):

![](i/punk7804_natural.png)   2x, 4x:
![](i/punk7804_natural@2x.png)
![](i/punk7804_natural@4x.png)



#### Alien Invasion

Let's try the green (120°) variant.
Let's make - a super rare alien
![](https://github.com/openpunkart/punks.blocks/raw/master/alien-invasion/alien-male_120.png)
with a capforward
![](https://github.com/openpunkart/punks.blocks/raw/master/basic/m/capforward.png),
smallshades
![](https://github.com/openpunkart/punks.blocks/raw/master/basic/m/smallshades.png)
and a pipe
![](https://github.com/openpunkart/punks.blocks/raw/master/basic/m/pipe.png)
from scratch:

```
$ magick convert alien-male_120.png \
                 capforward.png \
                 smallshades.png \
                 pipe.png \
         -background none -flatten punk7804_120.png
```

<!--
$ magick convert alien-male_120.png capforward.png smallshades.png pipe.png -background none -flatten punk7804_120.png

$ magick convert punk7804_120.png -filter point -resize 200% punk7804_120x2.png

$ magick convert punk7804_120.png -filter point -resize 400% punk7804_120x4.png
-->

![](i/punk7804_120.png)   2x, 4x:
![](i/punk7804_120@2x.png)
![](i/punk7804_120@4x.png)

Or try the 90° ![](https://github.com/openpunkart/punks.blocks/raw/master/alien-invasion/alien-male_90.png) variant - `alien-male_90.png`:

![](i/punk7804_90.png)   2x, 4x:
![](i/punk7804_90@2x.png)
![](i/punk7804_90@4x.png)

Or 150° ![](https://github.com/openpunkart/punks.blocks/raw/master/alien-invasion/alien-male_150.png) - `alien-male_150.png`:

![](i/punk7804_150.png)   2x, 4x:
![](i/punk7804_150@2x.png)
![](i/punk7804_150@4x.png)




### Alien with Cap

Let's make punk #2890 - another super rare alien
![](https://github.com/openpunkart/punks.blocks/raw/master/basic/alien-male.png)
with a cap
![](https://github.com/openpunkart/punks.blocks/raw/master/basic/m/cap.png)
from scratch:

```
$ magick convert alien-male.png \
                 cap.png \
         -background none -flatten punk2890.png
```

<!--
$ magick convert alien-male.png cap.png -background none -flatten punk2890.png
-->


![](i/punk2890.png)   2x, 4x:
![](i/punk2890@2x.png)
![](i/punk2890@4x.png)

Try the natural version ![](https://github.com/openpunkart/punks.blocks/raw/master/natural/alien-male-natural.png):

![](i/punk2890_natural.png)   2x, 4x:
![](i/punk2890_natural@2x.png)
![](i/punk2890_natural@4x.png)



#### All Caps

Let's try the red (0°) variant.
Let's make - a super rare alien
![](https://github.com/openpunkart/punks.blocks/raw/master/alien-invasion/alien-male.png)
with a cap
![](https://github.com/openpunkart/punks.blocks/raw/master/all-caps/m/cap_0.png)
from scratch:

```
$ magick convert alien-male.png \
                 cap_0.png \
         -background none -flatten punk2890_0.png
```

<!--
$ magick convert alien-male.png cap_0.png -background none -flatten punk2890_0.png

$ magick convert punk2890_0.png -filter point -resize 200% punk2890_0x2.png

$ magick convert punk2890_0.png -filter point -resize 400% punk2890_0x4.png
-->

![](i/punk2890_0.png)   2x, 4x:
![](i/punk2890_0@2x.png)
![](i/punk2890_0@4x.png)


Or try the blue (240°) ![](https://github.com/openpunkart/punks.blocks/raw/master/all-caps/m/cap_240.png) variant - `cap_240.png`:

![](i/punk2890_240.png)   2x, 4x:
![](i/punk2890_240@2x.png)
![](i/punk2890_240@4x.png)



### Humans with Cap

Or let's make a (light skintone) human punk
![](https://github.com/openpunkart/punks.blocks/raw/master/basic/human-male_light.png)
with a red (0°) cap
![](https://github.com/openpunkart/punks.blocks/raw/master/all-caps/m/cap_0.png)
and a smile
![](https://github.com/openpunkart/punks.blocks/raw/master/basic/m/smile.png)
from scratch:


```
$ magick convert human-male_light.png \
                 cap_0.png \
                 smile.png \
         -background none -flatten human_light.png
```

<!--
$ magick convert human-male_light.png cap_0.png smile.png -background none -flatten human_light.png

$ magick convert human_light.png -filter point -resize 200% human_lightx2.png
-->

![](i/human_light.png)   2x, 4x:
![](i/human_light@2x.png)
![](i/human_light@4x.png)


Or try the dark skintone ![](https://github.com/openpunkart/punks.blocks/raw/master/basic/human-male_dark.png) variant - `human-male_dark.png` -
with a green (120°) cap ![](https://github.com/openpunkart/punks.blocks/raw/master/all-caps/m/cap_120.png)  - `cap_120.png`:


<!--
$ magick convert human-male_dark.png cap_120.png smile.png -background none -flatten human_dark.png
-->


![](i/human_dark.png)   2x, 4x:
![](i/human_dark@2x.png)
![](i/human_dark@4x.png)


### Doge Shiba Inu - Much Wow

Let's make a doge punk  - a super rare alien
![](https://github.com/openpunkart/punks.blocks/raw/master/doge/alien.png)
with a headband
![](https://github.com/openpunkart/punks.blocks/raw/master/doge/headband.png)
from scratch:

```
$ magick convert alien.png \
                 headband.png \
         -background none -flatten doge3100.png
```

<!--
 $ magick convert alien.png headband.png -background none -flatten doge3100.png

 $ magick convert doge3100.png -filter point -resize 200% doge3100x2.png
  -->

![](i/doge3100.png) 2x, 4x:
![](i/doge3100@2x.png)
![](i/doge3100@4x.png)


Or let's make a zombie
![](https://github.com/openpunkart/punks.blocks/raw/master/doge/zombie.png)
with a knitted cap
![](https://github.com/openpunkart/punks.blocks/raw/master/doge/knittedcap.png)
from scratch:


```
$ magick convert zombie_notop.png \
                 knittedcap.png \
         -background none -flatten doge2066.png
```

<!--
 $ magick convert zombie_notop.png knittedcap.png -background none -flatten doge2066.png

 $ magick convert doge2066.png -filter point -resize 200% doge2066x2.png
  -->

![](i/doge2066.png) 2x, 4x:
![](i/doge2066@2x.png)
![](i/doge2066@4x.png)



Or let's make a classic
![](https://github.com/openpunkart/punks.blocks/raw/master/doge/classic.png)
with a 3d glasses
![](https://github.com/openpunkart/punks.blocks/raw/master/doge/3dglasses.png)
from scratch:


```
$ magick convert classic.png \
                 3dglasses.png \
         -background none -flatten doge_3dglasses.png
```

<!--
 $ magick convert classic.png 3dglasses.png -background none -flatten doge_3dglasses.png

 $ magick convert doge_3dglasses.png -filter point -resize 200% doge_3dglassesx2.png
  -->


![](i/doge_3dglasses.png) 2x, 4x:
![](i/doge_3dglasses@2x.png)
![](i/doge_3dglasses@4x.png)



And so on. Yes, you can.





## Bonus - ImageMagick Special Effects

Use the [free ImageMagick tools](https://imagemagick.org)
to script special effects (on the command line).


### Polaroid-Like Photos

Let's start with a "plain vanilla" punk, that is, #2890 ![](i/punk2890.png) and
let's use the 4x (96×96) version
and turn it into a captioned polaroid-like photo:

```
$ magick convert punk2890x4.png \
          -gravity center -set caption "Punk #2890" \
          -caption '%c' \
          -border 5x5 \
          -bordercolor AliceBlue -background black  +polaroid \
          polaroid2890.png
```

![](i/polaroid2890.png)


And let's try some more:

![](i/polaroid7804.png)
![](i/polaroid_human_light.png)
![](i/polaroid_human_dark.png)
![](i/polaroid_doge.png)




### Magnify 2x, 3x 4x with (Smooth) Pixel Art Scaling Algorithm

Let's start with a "plain vanilla" punk, that is, #2890 ![](i/punk2890.png) and
let's use 2x magnified (48×48) version
using a (smooth) [pixel art scaling algorithm¹](https://en.wikipedia.org/wiki/Pixel-art_scaling_algorithms)):

Note¹: ImageMagic uses the [scale2x](http://www.scale2x.it/algorithm) algorithm

<!--
  more on github @ https://github.com/amadvance/scale2x/
  -->


```
$ magick convert punk2890.png \
          -magnify \
          punk2890@magnify2x.png
```

![](i/punk2890@magnify2x.png)


And doubling again (4x):

```
$ magick convert punk2890.png \
          -magnify -magnify \
          punk2890@magnify4x.png
```

![](i/punk2890@magnify4x.png)

And doubling again (8x):

```
$ magick convert punk2890.png \
          -magnify -magnify -magnify \
          punk2890@magnify8x.png
```

![](i/punk2890@magnify8x.png)



And let's try some more:

![](i/punk7804@magnify2x.png)
![](i/punk7804@magnify4x.png)
![](i/punk7804@magnify8x.png)
![](i/human_light@magnify2x.png)
![](i/human_light@magnify4x.png)
![](i/human_light@magnify8x.png)


![](i/doge@magnify2x.png)
![](i/doge@magnify4x.png)
![](i/doge@magnify8x.png)



Power Tip - Let's retry with the [high quality scale (hqx)
pixel art scaling algorithm family](https://en.wikipedia.org/wiki/Hqx) in the 2x, 3x and 4x variants.

Note:  A free ImageMagick tools installation gets you
a copy of ffmpeg. Let's try:

```
$ ffmpeg -i punk2890.png \
          -filter_complex hqx=2 \
          punk2890@hq2x.png
```

![](i/punk2890@hq2x.png)

And 3x:

```
$ ffmpeg -i punk2890.png \
          -filter_complex hqx=3 \
          punk2890@hq3x.png
```

![](i/punk2890@hq3x.png)

And 4x:

```
$ ffmpeg -i punk2890.png \
          -filter_complex hqx=4 \
          punk2890@hq4x.png
```

![](i/punk2890@hq4x.png)


And let's try some more:

![](i/punk7804@hq2x.png)
![](i/punk7804@hq3x.png)
![](i/punk7804@hq4x.png)
![](i/human_light@hq2x.png)
![](i/human_light@hq3x.png)
![](i/human_light@hq4x.png)


![](i/doge@hq2x.png)
![](i/doge@hq3x.png)
![](i/doge@hq4x.png)



And so on. Yes, you can.




## Questions? Comments?

Post them over at the [Help & Support](https://github.com/geraldb/help) page. Thanks.


