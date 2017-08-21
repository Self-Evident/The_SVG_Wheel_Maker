# D Wheel Maker & Spoke Length Calculator



--------------------------------------------------------------------------------
## Contents:
- [Demo](#demo)
- [Description](#description)
- [Disclaimer](#disclaimer)



--------------------------------------------------------------------------------
## <a name=demo></a>Demo

- Just download & try the [current version](https://raw.githubusercontent.com/Self-Evident/The_SVG_Wheel_Maker/master/The_SVG_Wheel_Maker.html) - it's one file!
  



## <a name=description></a>Description

TL;DR: The coolest spoke length calculator you've ever seen!


Long version:

There are plenty of spoke length calculators out there.  And they all seem to work well.  But, one day I decided I wanted to know the math, so I wrote one. Because, why not.

This porject is the current result of that effort. (And there were many variations/iterations/alterations in before it.)

To try it out, get the latest version from above.  It's a simple html/javascript file, so you can save it anywhere local on your computer. Then open it up in a web browser (Firefox, Chrome, etc).  It doesn't need to run from a web server. It can run from your computer directly. 

Now, as indicated above, this is not just your average everyday spoke length calculator.  No, this one raises the bar, several times.  For starters, after spoke lengths, it provides some "advanced" build information, such as bracing angles & spoke tension ratios - but not just for the "center flange" (ie: average) approximations: it also provides the values for spokes laced both elbows in and elbows out.

Additionally, it also has options for standard, triplet, and custom lacing patterns (and possibly in the future, paired holed hubs and rims).  That is, in "triplet" mode for example, there is no need for figuring non-integer "spoke cross" values.  In both standard & triplet modes, it suggests appropriate spoke cross values (all integers) based on rim/hub spoke hole counts.

As useful as all the of that is, the most interesting, and unique, feature of this calculator is that it actually draws the wheel on screen!  It's nothing fancy: no 3-d rendering or views, but it produces a pretty cool image none-the-less, even if I do say so myself.

And finally, for the icing on this cake, it has options for customizing the display of the wheel, such as showing/hiding spoke groups, or the rim, changing colors, etc.


## <a name=disclaimer></a>Disclaimer

Like every spoke length calculator, this is a simple utility, and can not determine the validity of every possible combination of rim and hub values.

That is, just because the program many generate a theoretical wheel on screen from a given set of inputs, does not guarantee that such a wheel is realistically practical, or possible. Or even that all required spokes lengths are listed.  The preceding will more likely become evident in Custom mode, as it has fewer restrictions on rim & hub values than Standard & Triplet modes.  And while it will generally be obvious when values produce an unrealistic wheel, again, there are no guarantees.

For additional information, please refer to geometry. And physics.
