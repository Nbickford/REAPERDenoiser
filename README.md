# REAPER Denoiser Tutorial Source Code

*micsthepick is now maintaining a fork of this denoiser with higher quality! https://github.com/micsthepick/REAPERDenoiser/tree/minphase*

This repository contains source code for [a tutorial](https://www.neilbickford.com/blog/2020/02/02/a-real-time-jsfx-audio-denoiser-for-reaper/) showing how to write a JSFX denoiser for REAPER based on Norbert Weiner's [deconvolution algorithm](https://en.wikipedia.org/wiki/Wiener_deconvolution). This reduces some of the artifacts you get when using a REAFir subtraction-based approach, but also removes noise more gently. You can also set the Noise Scale value to high levels [to produce a bell-like effect](https://www.neilbickford.com/blog/wp-content/uploads/2020/02/out.mp4)!

This denoiser was used to remove background noise for several GME videos, including the Celeste Celeste Collections videos. Now, it's open-source!

[![Grant Huang playing *Quiet and Falling* and *In the Mirror* from *Celeste* on a celeste.](https://img.youtube.com/vi/_-92lvJd3g4/0.jpg)](https://www.youtube.com/watch?v=_-92lvJd3g4)

For more information about the denoiser, please see the accompanying blog post at https://www.neilbickford.com/blog/2020/02/02/a-real-time-jsfx-audio-denoiser-for-reaper/.

## Installing This Plugin

This JSFX plugin can be installed like most other JSFX plugins:

1. Open the REAPER resource folder by opening REAPER and then selecting Options > "Show REAPER resource path in explorer/finder..." from REAPER's menu bar.
2. Download the REAPERDenoiser JSFX file by clicking on REAPERDenoiser above, clicking on "Raw", and saving the file, or directly from https://raw.githubusercontent.com/Nbickford/REAPERDenoiser/main/REAPERDenoiser.
3. Move the REAPERDenoiser JSFX file into the Effects directory that you opened in step 1.

That's it!
