---
title: "How secure is your build/server?"
draft: false
image : images/speakers/patric-debois.png
twitter: "https://twitter.com/patrick-debois"
type: "talk"
speakers: ["patrick-debois"]
---

Development has changed over the years, from doing everything yourself to a 3rd party package for every function. Operations has changed too, running your own servers is now considered an exception. To the cloud!
We have learned that we need to trust others , but as our parents used to say - don’t trust strangers. So we secure our production server more than ever.

Yet, in the middle sits this no-man's land : “the build server”. We think it’s time to take a closer look at some of the good practices around securing builds & artifacts to improve our day to day level of trust.

With Marked Sherman statement “Development is now assembly” in mind, the talk will focus more on the package/artifact/repository aspect. Less on the app security inside the code itself or at the OS/Machine level.

This talk I will go into detail on:

- How to verify trust of your dependencies: from metadata , binaries and repositories
- How to provide trust to others that build upon your software
- How this ties into the concept of “reproducible builds”
- How a practical “Software Bill of Material” looks 
- How the concepts of the “The Update Framework” (TUF) relate
- How you can implement secure packaging policies

It will explain these topics using practical/code examples from the Nodejs and Docker ecosystems. 
All this will be presented from the different viewpoints from “dev” , “sec” and “ops”.

Let’s take ownership of your trust , we are already responsible when things go wrong anyway.
