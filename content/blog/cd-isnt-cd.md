---
title: "Continuous Delivery isn't Continuous Deployment"
date: 2019-12-19T21:08:43Z
draft: false
author: "Ken Mugrage"
---

We had an interesting discussion at a DevOps meetup the other day. A surprising revelation came out of the discussion - that many folks believed that Continuous Delivery and Continuous Deployment are the same thing - an approach where every commit must end up in production. Unsurprisingly, many were wary of even considering implementing Continuous Delivery. 

[Jez Humble](/speakers/jez-humble/) and [Dave Farley](/speakers/dave-farley/), both of whom are speaking at DeliveryConf 2020 in Seattle, wrote the book "Continuous Delivery". On Jez's website, https://www.continuousdelivery.com/ he defines Continuous Delivery as follows...

> Continuous Delivery is the ability to get changes of all types—including new features, configuration changes, bug fixes and experiments—into production, or into the hands of users, safely and quickly in a sustainable way.

Notice that his definition says *the ability* to get changes into production. An ability, but not a requirement.  

If you're creating a web application, it might be ok to automatically push to production when all the tests pass. As long as you're taking good care of user experience, it's a great way to get features into the hands of users as soon as possible so that you can start learning from them.

On the other hand, if you work on the Photoshop team at Adobe *please* don't go to a model where I have to download and install every good build!

In either case, you should be striving to ensure that you *can* deploy to production at any time. Not just on demand, *at any time*. This allows you to react when (not if) something like a security alert or critical bug or competitor action or any number of other things happen. Because they will, inevitably, happen. 

The talks at DeliveryConf will be about Continuous Delivery. Many of the speakers and attendees may have chosen to automate the final release step, and many may not. 

Don't let the term Continuous Delivery scare you. It doesn't mean that you have to push every single change out to your users whether you want  to or not. 

And come to DeliveryConf, where you'll learn how Continous Delivery, and even Continuous Deployment doesn't have to be scary!

