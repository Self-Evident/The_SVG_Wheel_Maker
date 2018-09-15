# D Wheel Maker & Spoke Length Calculator



--------------------------------------------------------------------------------
## Contents:
- [Demo](#demo)
- [Description](#description)
- [Disclaimer](#disclaimer)



--------------------------------------------------------------------------------
## <a name=demo></a>Demo

- Just download & try the [current version](https://raw.githubusercontent.com/Self-Evident/The_Wheel_Maker/master/The_Wheel_Maker.html) - it's one file!
  



## <a name=description></a>Description

TL;DR: The coolest spoke length calculator you've ever seen!


Long version:

There are plenty of spoke length calculators out there.  And they all seem to work pretty well.  But, one day I decided I wanted to know the math. So I did the math, and I wrote one. Because [what's one more??](https://xkcd.com/927/). :)

This project is the current result of that effort. (With many variations/iterations/alterations before it.)

To try it out, just get the latest version from above.  It's a single html/javascript file, so you can save it anywhere local on your computer. Then open it up in a web browser (Firefox, Chrome, etc).  It doesn't need to run from a web server, it can run as a local file. 

Now, as indicated above, this is not just your average everyday spoke length calculator.  No, this one raises the bar, several times.  For starters, after spoke lengths, it provides some "advanced" build information, such as bracing angles & spoke tension ratios - but not just for the "center flange" (ie: average) approximations: it also provides the values for spokes laced both elbows in and elbows out.

Additionally, besides standard wheels, it has options triplet lacings, custom lacing patterns, paired-hole hubs, paired-hole rims, and most combinations thereof.  And there is no need for you to figure some non-integer "spoke cross" value first for any of them.  Such math is handled automatically - you just enter the desired actual cross: 1, 2, 3, etc.

And not to stop there, in most modes, The Wheel Maker suggests appropriate spoke cross values (all integers) based on rim/hub spoke hole counts (except in custom mode).  Of course, such suggestions, along with most values, can be changed as desired.

But, as useful as all of that is, the most interesting, and unique, feature of this calculator is that it actually draws the wheel on screen!  It's nothing fancy: no 3-d rendering or views, but it produces a pretty cool image none-the-less. So, it's easy to get a good idea of what the real wheel will look like.

And finally, for the icing on this cake, it has options for customizing the display of the wheel, such as showing/hiding spoke groups, or the rim, changing colors, zoom in/out, etc.


## <a name=disclaimer></a>Disclaimer

Like every spoke length calculator, this is a simple utility, and can not determine the validity of every possible combination of rim and hub values.

That is, just because the program many generate spoke lengths and a theoretical wheel on screen from a given set of inputs, does not guarantee that such a wheel is realistically practical, or even possible. Or even that all required spokes lengths are listed.  The preceding will more likely become evident in Custom mode, as it has fewer restrictions on rim & hub values than the other modes/wheel types.  And while it may be obvious when values produce an unrealistic wheel, again, there are no guarantees.

For additional information, please refer to geometry. And [Sheldon](https://www.sheldonbrown.com/).
