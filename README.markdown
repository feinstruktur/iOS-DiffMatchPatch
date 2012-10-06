Obj-C Diff, Match and Patch Library as an iOS universal framework
===============================================
A simple way to use the classic DiffMatchPatch library as a drop-in iOS universal (i.e. runs on device and in the simulator) framework.

* Derived from the [DiffMatchPatch library](http://code.google.com/p/google-diff-match-patch/).
* Forked from the [Objective-C port by JanX2](https://github.com/JanX2/google-diff-match-patch-Objective-C).
* Uses the [iOS Universal Framework project template](https://github.com/kstenerud/iOS-Universal-Framework).


Instructions for use
-----

I've included frameworks compiled with iOS6 SDK and a choice of iOS4.3 or iOS5 as the target. If you want to use one of those, you can just drag and drop the one you want into your Xcode project.

If you want to compile your own, simply open the Xcode project, set the SDK and target as you require, and run in simulator. The compiled framework (*DiffMatchPatch.framework*) can then be found under *Products* in Xcode, by right-click > show in Finder.

If you don't know whether to use the *embeddedframework* or the *framework*, see the [iOS Universal Framework readme](https://github.com/kstenerud/iOS-Universal-Framework).