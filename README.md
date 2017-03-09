# CustomSegmentedControl

A customized segmented control on Objective-c

##Requirements##

Xcode 6 or later

##Manual Install:##

All you need to do is drop Source folder into your project and include headers.

##Configure SegmentedControl in code##
```
NSArray *arr = [NSArray arrayWithObjects: @"Trending", @"Random", @"Search", nil];
segmentControl = [[GIFSegmentedControl alloc] initWithFrame:CGRectMake(0, 0, 250, 30)];
segmentControl.items = arr;
segmentControl.selectedIndex = 0;
[segmentControl addTarget:self action:@selector(segmentValueChanged:) forControlEvents:UIControlEventValueChanged];
```

##With Storyboards##

######Add UIView to Storyboard:######

![alt tag](https://s23.postimg.org/stpagzju3/2017_03_09_11_44_42.png)

######Select class:######

![alt tag](https://s23.postimg.org/oy6a3ny6z/2017_03_09_11_45_08.png)

######Setup Segmented Control:######

![alt tag](https://s29.postimg.org/3xiwshfyf/2017_03_09_11_48_20.png)

##Result##

![alt tag](http://i.giphy.com/3oKIPgmkgHPazgmifC.gif)
