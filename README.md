This is part of a full piece over on my RK Color website. Read more here: https://rkcolor.com/blog/does-film-look-better-than-digital/ 

# Studying Elements of Depth Across Film and Digital
As I mentioned earlier, if we define a good looking image as an image that has perceived depth, we can begin to use that depth as a proxy to study what makes an image look good.

Outside of compositional elements, an image can create depth through contrast in luminance and color. It’s the difference between light and shadow and differences between colors that create this depth.

Take a look at the below paintings by Mark Rothko. I feel that mark’s paintings help illustrate this idea of depth through contrast in isolation from layering of objects and composition – at least the best that we possibly can.

In the first one here, Untitled, we have the absense of color, with only a black and grey blocks. Despite such little information being present in the frame, it still feels like there’s just enough here to find a sense of depth to the flat image.

https://www.wikiart.org/en/mark-rothko/untitled-1969-2/

Similarly we have the painting “Number 61.” While relatively similar lumanice values across the three colors, we have distinct differences in hue. Particularly the red and blue – notably approaching opposite each other on a color wheel. Not quite, but still a large jump in color contrast.

And again, there seems to be just enough to find that feeling of depth.

https://www.wikiart.org/en/mark-rothko/no-61-rust-and-blue/

## Achieving Luminance Contrast From An Intermediate Color Space

To simplify the discussion, I want to take a look at how film is “interpreting” contrast information across luminance data. To do this, I took the same shot of a chart and compared the transformation to Rec.709 with several film stock profiles using Dehancer.

Of course this requires us to rely on Dehancer’s color science – though from what they’re doing I don’t doubt it. Though I do also plan to do a version of this test on various film stocks in the future to add to this comparison in the future.

Various charts run through rec709 transforms or film emulations
Next, I extracted the luminance values from the middle exposure strips, which in my Spyder Checker Photo chart consists of 10% steps (plus a 5% step at 5% black).

I then analyzed the changes from an intermediate color space (in this case, DaVinci Wide Gamut Intermediate) to the final image output. While any of these profiles or transforms could create an aesthetically pleasing image from a DWG image, comparing the differences reveals _how_ it happened. From here, we can begin to draw conclusions.

The first thing of note is that all profiles tend to increase global contrast by raising highlight values and lowering shadow values. However, there is greater variance in how each method achieves this global contrast increase. The ratios and areas where contrast is altered, and the degree of change, vary from chart to chart. These differences in handling specific regions create smaller pockets of contrast with distinct characteristics between charts or images.

You will also notice that the neutral (Rec.709 transform) image still exhibits these regional variants, similar to a film stock, though in different ways.

This ultimately points to achieving the same goal: an increase in global contrast with regional variations. However, the extent of the contrast increase and the degree of variation throughout the spectrum are managed in their own unique ways.

### Some Notes, Flaws, And Future Updates With The Study
In the future, I plan to revisit this study to examine saturation versus luminance and explore methods to analyze changes in hue. I also want to perform the same study while incorporating developed film. I’ll be revisiting and updating this post at a later date.

If you’re reading this (and I know that you are), I have yet to do this.

There are a few potential flaws in the study that I’ll try to correct when I conduct it again:
- I wasn’t highly scientific in maintaining consistent middle grey.
- The lighting conditions for my chart weren’t very precise.
- I’m not a color scientist, so some underlying assumptions could be incorrect. I’m just a guy on the internet doing experiments.
