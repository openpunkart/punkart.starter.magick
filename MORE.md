# More ImageMagic Command Line Examples


## Wall Street Bets

Let's make a (light skintone) human punk
![](../punks.blocks/basic/human-male_light.png)
with regular shades
![](../punks.blocks/basic/m/regularshades.png)
and a wall street bets hairdo
![](../punks.blocks/misc/wallstreetbets-hair.png)
from scratch:


```
$ magick convert human-male_light.png \
                 wallstreetbets-hair.png \
                 regularshades.png \
            -background none -flatten wallstreetbets_human_light.png
```

![](i/wallstreetbets_human_light.png)  4x ![](i/wallstreetbets_human_light@4x.png)


Let's add a smile ![](../punks.blocks/basic/m/mile.png):


```
$ magick convert human-male_light.png \
                 wallstreetbets-hair.png \
                 regularshades.png \
                 smile.png \
            -background none -flatten wallstreetbets_human_light_smile.png
```

![](i/wallstreetbets_human_light_smile.png) 4x  ![](i/wallstreetbets_human_light_smile@4x.png)


Let's add a pipe ![](../punks.blocks/basic/m/pipe.png):


```
$ magick convert human-male_light.png \
                 wallstreetbets-hair.png \
                 regularshades.png \
                 smile.png \
                 pipe.png \
            -background none -flatten wallstreetbets_human_light_pipe.png
```

![](i/wallstreetbets_human_light_pipe.png) 4x ![](i/wallstreetbets_human_light_pipe@4x.png)


Let's try a super rare alien ![](../punks.blocks/basic/male-alien.png):

```
$ magick convert alien-male.png \
                 wallstreetbets-hair.png \
                 regularshades.png \
            -background none -flatten wallstreetbets_alien.png
```

![](i/wallstreetbets_alien.png) 4x ![](i/wallstreetbets_alien@4x.png)


Let's change to 3D glasses ![](../punks.blocks/basic/m/3dglasses.png):

```
$ magick convert alien-male.png \
                 wallstreetbets-hair.png \
                 3dglasses.png \
            -background none -flatten wallstreetbets_alien_3dglasses.png
```

![](i/wallstreetbets_alien_3dglasses.png) 4x ![](i/wallstreetbets_alien_3dglasses@4x.png)



And so on. Yes, you can.


