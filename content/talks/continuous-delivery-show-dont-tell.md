---
title: "Continuous Delivery - Show, Don't Tell"
draft: false
image : images/speakers/coming-soon-logo.png
twitter : "https://twitter.com/jprelph"
type: "talk"
speakers: ["james-relph"]
---

Working on a large and time critical project for a UK Public Sector body, we were told very clearly that the stakeholders didn't think "continuous delivery" was suitable for their organisation. We disagreed, but while we could have argued (and lost), we decided to show to them that it was suitable. To do this we leveraged a range of technical solutions to prove to the stakeholders that they could do continuous delivery safely. 

We took an approach to using Helm charts which embedded significant metadata within the charts, standardising as much boilerplate code as possible and proving reduced risk. We leveraged a sidecar model within Kubernetes pods to minimise changes to application service code which didn't introduce new features. Finally we worked with the test team to develop a highly automated Serenity-based test framework, deployed within Kubernetes, to test quickly, cost effectively, reliably, and to share the results in a format which built confidence in our process. 

This talk will cover some of the technical approaches and challenges that allowed us to move this project from a "one a fortnight" release cadence to being able to take features from ticket to production, within 50 minutes.
