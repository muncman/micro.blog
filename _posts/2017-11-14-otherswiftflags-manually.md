---
layout: post
title: "OTHER_SWIFT_FLAGS Manually"
microblog: false
audio: 
photo: http://muncman.micro.blog/uploads/2017/1094daef6c.jpg
date: 2017-11-13 22:36:23 -0500
guid: http://muncman.micro.blog/2017/11/14/otherswiftflags-manually.html
---
The "Swift Compiler - Custom Flags” section showed up in Build Settings for a project’s Test target, not the main target. 

The problem was that I wanted it at (the project level and) main target (for `#if`use in Swift). I manually edited it into the project.pbxproj --- and it worked the first time! 

After a day of fighting with Xcode *even more than normal*, that was nice. 

<img src="http://muncman.micro.blog/uploads/2017/1094daef6c.jpg" width="600" height="338" />
