---
title: "June in Servo: real world compat, media queries, SharedWorker, and more!"
url: "https://servo.org/blog/2026/07/31/june-in-servo/"
date: "2026-07-31"
feed_url: "https://servo.org/blog/feed.xml"
---
Servo 0.4.0 contains all of the changes we landed in June, which came out to yet another record 558 commits (April: 534, May: 391). For security fixes, see § Security . We’ve shipped several new web platform features: ‘attr()’ , in experimental mode ( @Loirooriol , #45041 ) ‘image( )’ , ‘closest-corner’ , and ‘farthest-corner’ in ‘ellipse()’ and ‘circle()’ ( @Loirooriol , #45421 ) ‘calc()’ and other mathematical expressions can now be resolved later than parse time, e.g.
