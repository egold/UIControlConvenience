UIControlConvenience
====================

A category on UIControl to provide convenience when working with UIKit controls programmatically. For now, a pretty small category, but will add to it as needs demand.

Usage
-----

Removing all actions on a UIButton:

```objc
#import "UIControl+Convenience.h"

-(void)someMethod
{
    [myButton removeAllTargetActionEvents];
}

```

Installation
-----

Drag UIControl+Convenience.h and UIControl+Convenience.m to your project, or add project as dependency to your own project.