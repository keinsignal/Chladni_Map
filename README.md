# Chladni_Map
Inspired by a recent video on Steve Mould's channel about Chladni figures, aka 2D standing waves.
https://www.youtube.com/watch?v=rjueHI002Fg&t=266s

The formula is given as $$f(x,y) = sin(xmπ) &times; sin(ymπ) &minus; sin(xnπ) &times; sin(ynπ)$$. Steve plugs this into Desmos to show the intricate, symmetric patterns created by mapping out the zeroes of this function, but I wanted to see it as a full colormap.

In the end the colormap approach seemed a bit muddy and uninteresting, generally just reproducing some variation on plaid, so I dialed it back to use fewer colors and also tried a version that just maps a few of the integer points as contours. However, it's likely the muddiness was in part caused by a flaw in the code, that wasn't properly clearing the canvas before updating it.

The interested user is invited to take this mess and do whatever they like with it, feel free to share any particularly spectacular results you may come up with.
