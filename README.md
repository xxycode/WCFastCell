#This project is no longer maintained

This project will not do any good for your application. GPUs are good at composition, and drawing in `drawRect:` is extremely inefficient.

**Please do not use it**

I also updated the test project so that you can see how inefficient it is :).

==========


###What it is?
WCFastCell is a drop in replacement for UITableViewCell & UICollectionViewCells. It draws subviews' contents (either UILabels or UIImageViews) on a single layer. Thanks to that UITableViews & UICollectionViews scroll more smoothly. It can be especially useful on older devices.

###What it isn't?

If you need to animate cell's contents you should not use WCFastCell, but in other cases you are free to use it.


### UITableViewCells vs WCFastCells
<img src="/README%20resources/UITableViewCell.tiff" height="500px">
<img src="/README%20resources/WCFastCell.png" height="500px">

![](/README\ resources/Performance\ difference.png)

#####Device: iPhone 4
###### UITableViewCells: ~35 FPS
###### WCFastCells: ~60 FPS

###License
Copyright (c) 2013-2014 Wojciech Czekalski. All rights reserved.

WCFastCell is free and open source code, licensed under MIT. See LICENSE for full details.

###About me

[Twitter: @wczekalski](http://twitter.com/wczekalski)
