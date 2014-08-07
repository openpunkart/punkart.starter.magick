# statistics

Beer statistics (production in hl, consumption per capita, imports, exports, breweries, etc.).
Example:


## List of countries by beer consumption per capita


|            | Country            |         Consumption |          Production |     # Breweries |
| ---------: | ------------------ | ------------------: | ------------------: | --------------: |
|    145 (l) | Czech Republic     |      15583 (000 hl) |      18181 (000 hl) |    55 breweries |
|    108 (l) | Austria            |       9105 (000 hl) |       8917 (000 hl) |   170 breweries |
|    107 (l) | Germany            |      87655 (000 hl) |      95545 (000 hl) |  1341 breweries |
|     95 (l) | Lithuania          |       2932 (000 hl) |       2922 (000 hl) |    73 breweries |
|     95 (l) | Poland             |      36007 (000 hl) |      37854 (000 hl) |   117 breweries |
|     89 (l) | Romania            |      17000 (000 hl) |      16900 (000 hl) |    20 breweries |
|     87 (l) | Finland            |       4732 (000 hl) |       4220 (000 hl) |    25 breweries |
|     86 (l) | Ireland            |       4721 (000 hl) |       8514 (000 hl) |    26 breweries |
|     85 (l) | Croatia            |       3683 (000 hl) |       3737 (000 hl) |     6 breweries |
|     85 (l) | Luxembourg         |        325 (000 hl) |        330 (000 hl) |     3 breweries |
|     81 (l) | Slovenia           |       1685 (000 hl) |       1640 (000 hl) |     ? breweries |
|     78 (l) | Belgium            |       8574 (000 hl) |      18571 (000 hl) |   123 breweries |
|     74 (l) | Latvia             |       1626 (000 hl) |       1529 (000 hl) |     ? breweries |
|     73 (l) | United Kingdom     |      44843 (000 hl) |      45694 (000 hl) |   946 breweries |
|     72 (l) | Slovakia           |       3997 (000 hl) |       3123 (000 hl) |     5 breweries |
|     71 (l) | Estonia            |        960 (000 hl) |       1360 (000 hl) |     6 breweries |
|     71 (l) | Netherlands        |      11974 (000 hl) |      23644 (000 hl) |   125 breweries |
|     69 (l) | Bulgaria           |       5100 (000 hl) |       4820 (000 hl) |     8 breweries |
|     68 (l) | Denmark            |       3654 (000 hl) |       6590 (000 hl) |   150 breweries |
|     65 (l) | Hungary            |       6464 (000 hl) |       6249 (000 hl) |     ? breweries |
|     59 (l) | Norway             |       2426 (000 hl) |       2346 (000 hl) |    32 breweries |
|     57 (l) | Switzerland        |       4626 (000 hl) |       3546 (000 hl) |   360 breweries |
|     53 (l) | Portugal           |       5320 (000 hl) |       8299 (000 hl) |     7 breweries |
|     51 (l) | Cyprus             |        450 (000 hl) |        316 (000 hl) |     2 breweries |
|     50 (l) | Sweden             |       4806 (000 hl) |       4491 (000 hl) |    65 breweries |
|     48 (l) | Spain              |      35196 (000 hl) |      33573 (000 hl) |    88 breweries |
|     45 (l) | Malta              |        189 (000 hl) |        127 (000 hl) |     1 breweries |
|     35 (l) | Greece             |       4005 (000 hl) |       3700 (000 hl) |    17 breweries |
|     30 (l) | France             |      20000 (000 hl) |      15910 (000 hl) |   442 breweries |
|     29 (l) | Italy              |      17715 (000 hl) |      13410 (000 hl) |   391 breweries |
|     10 (l) | Turkey             |       8244 (000 hl) |       9212 (000 hl) |    11 breweries |


## Sources

### `consumption.csv`

- Country
- Year in 1000 hl (1 hl = 100 l) = 100_000 l   (l=liter; hl hectoliter)

~~~
Country,2011 (000 hl),2010 (000 hl),2009 (000 hl)
Austria,9105,8878,8905
Belgium,8574,8439,8680
...
~~~

### `consumption_per_capita.csv`

- Country
- Year in l (l=liter)

~~~
Country,2011 (l),2010 (l),2009 (l)
Austria,108.1,105.8,106.5
Belgium,78,78,81
...
~~~

### `breweries.csv`

- Country
- Number of Breweries - in brackets microbreweries (optionally) e.g. 170 (97)

~~~
Country,2011,2009
Austria,170 (97),172
Belgium,123,123
...
~~~


## Questions? Comments?

Send them along to the
[Open Beer, Breweryn n Brewpub Data Forum/Mailing List](http://groups.google.com/group/beerdb).
Thanks!

