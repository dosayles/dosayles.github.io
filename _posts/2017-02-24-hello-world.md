---
layout: post
title: "Proverbial Hello World..."
date: 2017-02-24 10:00:00
tags: [hadoop]
---

So first post testing out...the normalized junk that serves as a notice that yes, this is the very first testing out post to the net.

This weekend I'm iterating through additional mapper/reducer code to run on the Hadoop cluster. I'm encouraged by the progress made, but more importantly about the learning that is sticking.  Approaching programming for Hadoop from an infrastructure perspective has been beneficial to understanding the distributed nature.  In short, Hadoop is all about bringing the code to the data, which is a different way of thinkin' for an infrastructure cat. Exploring this further will be the intent of the next few posts.

# Thoughts around conceptualization...

Getting started with Hadoop overall requires a shift in thinking. Any shift in thinking should not be foreign to an IT geek trying to figure stuff out in today's world or at any other time for that matter. The very fabric of compute and technology is continuous advancement...stagnation is death of revelance.  You can extrapolate this to a vendor or the crusty UNIX guy in the corner.  The micro-second either say "cool, we're good" showing an unwillingness to think differently about problems...they're TOAST.

![Dilbert's UNIX dude](/images/cartoon_dilbert_condescending_unix_user_204x194.png)

# Methodology with Hadoop...
The primary method to change your thoughts with Hadoop today involves how you manifest your realization of data in your mind.  When you think of "data" today, what do you visualize? Are thinking of a spreadsheet?  Rows? Columns? A Number?  An entity?  Perhaps bigger, at a Database level?  Are you thinking of an Oracle database?

The mind's eye should reduce data to the key-value pair at the fundamental level.  Learn it...love it.  Its your future, and if you will, its been quite a large part of the past as well.  Heres a bit on what the key-value pair (KVP) is: [Key-value pair greater definition](https://en.wikipedia.org/wiki/Attribute%E2%80%93value_pair "Attribute-value pair on Wikipedia")

From a developers perspective, or anyone who works with data at its fundamental level, the key-value pair (KVP) is the foundation of organization. Constructs can be intermixed and managed through manifestation of objects. Depending upon the language, collections are organizations of KVPs. Envisioning the spreadsheet row object, one may visualize the column A parameter as the key, and the remaining columns data (say B:E) as a "collection" of values.  The collection as a whole is the value for the KVP object.

My intention is to further explore Hadoop interworkings in this manner...basics for most, yet hopefully pulling some along as well.
