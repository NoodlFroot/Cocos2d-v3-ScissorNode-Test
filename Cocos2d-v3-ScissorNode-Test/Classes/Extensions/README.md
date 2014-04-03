ClippingNode
============

Provides a CCNode type [CCScissorNode] which can be used for clipping the visible area of children


This has been sourced from:
* http://www.cocos2d-iphone.org/forum/topic/32102
* http://www.cocos2d-iphone.org/forum/topic/19341
* http://www.learn-cocos2d.com/2011/01/cocos2d-gem-clippingnode/

* Forked from https://github.com/njt1982/ClippingNode for cocos2d v3 work

Usage
======
```objectivec
CGRect menuBoundaryRect = CGRectMake(x, y, width, height);
CCScissorNode *clipNode = [CCScissorNode scissorNodeWithRect:menuBoundaryRect];
[clipNode addChild:menu];
[menu fixPosition];
[self addChild:clipNode];
```
