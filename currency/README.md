# currency.csv Datasets - All Currency Meta Data / Attributes - Spot Colors / Characteristics


## Original Series

> To identify the different characteristics that make each artwork unique,
> we used something called a neural network.
> The algorithm converts each pixel of the artwork into data,
> translates this data into specific features of the work,
> and compares the differences between the different works.
>
> From the amount of drips and splashes, to the texture of the paint,
> each artwork has a unique combination of features.
>
> About colors:
>
> On each artwork, the color of every spot is unique. Even if two blue spots
> look similar, they will be different shades of blue.
> However, the colour rarity feature looks at each pixel of the artwork and
> classifies it into a color group.
> We mapped 10,000 RGB values and divided
> them into seven color groups: Blue, Red, Green, Yellow, Magenta, Black, White.
>
> The amount of colored pixels are scored using a percentage,
> which indicates the percentage of pixels of that artwork
> that is a certain color.
>
> For example, in the artwork #9038. We see 12% of the pixels
> are green which ranks it 6,304 out of 10,000.
> This means that 6,303 artworks have fewer green pixels and 3,697 have more.
>
>  -- [Rarities @ Damien Hirst's "The Currency"](https://currency.nft.heni.com/rarities
)



Currency spots dataset in comma-separated values (CSV) format
in blocks of a thousand each.
The data records for currency spots
incl. number (starting with 1),
colors (whites, reds, blues, greens, yellows, magentas, blacks)
and characteristics (overlaps, density, texture, drips, weight).
Example:

```
number, whites, reds, blues, greens, yellows, magentas, blacks, overlaps, density, texture, drips, weight
1, 0.402392, 0.162989, 0.155047, 0.112621, 0.089125, 0.071828, 0.005998, 0.38092, 0.333361, 0.381266, 0.425299, 16.76
2, 0.390161, 0.174939, 0.147431, 0.115006, 0.091361, 0.0667, 0.014401, 0.460834, 0.550324, 0.47306, 0.480488, 17.7
3, 0.38945, 0.172346, 0.143954, 0.128668, 0.08226, 0.066863, 0.016459, 0.472569, 0.483081, 0.493204, 0.508468, 16.84
4, 0.385703, 0.169231, 0.155385, 0.119111, 0.087678, 0.066753, 0.016138, 0.504198, 0.525523, 0.466175, 0.513431, 15.65
5, 0.373726, 0.177796, 0.15209, 0.117613, 0.092, 0.071373, 0.015401, 0.391081, 0.658856, 0.594865, 0.515012, 17.48
...
```




## Questions? Comments?

Post them on the [CryptoPunksDev (& CurrencyArtDev) reddit](https://old.reddit.com/r/CryptoPunksDev). Thanks.