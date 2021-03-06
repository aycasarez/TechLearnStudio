---
layout: post
title:  "The Non Stop Thrill Ride That Is Omeka"
date:   2018-10-17 16:28:01 -0500
categories:
---

I am happy to report a solution after posting to a different sub-forum about my batch upload issue using the CSV Import Plug-in and the VRA Core plug-in.

The solution is...there isn't one!

https://forum.omeka.org/t/issue-with-vra-core-plugin-batch-uploading-with-csv-import/7237

Unfortunately, there is no way to batch upload records and to map some csv columns to VRA Core **sub-elements**. As disappointing as it is, I am at least somewhat self-assured that I received that information from very reliable sources- an Omeka.org employee and an apparent Omeka expert. 

I thought this was it but again my IRL/offline community of practice came through! Allyssa (the digital scholarship librarian) mentioned that I could create a new "Item Type" to bypass my issue. There are pre-created Item Types in Omeka such as "Still Image" or "Text". By creating my own Item Type, I can essentially dictate how I want to organize my information. In this case, I want to organize my information using VRA Core elements and sub-elements and be able to automatically map my CSV columns to each of those elements. 

This was a ten minute conversation and offered immense relief from a week of intense anxiety. In some ways, I feel like the offline communtiy of practice can be more useful because I can display my technical issues and work with others to find alternatives. Of course online communities can offer quicker feedback in comparison, but being able to show Allyssa my problem in real time also allowed her to offer more specific feedback. 

While speaking to the PI of my other digital humanities project, I realized I could also integrate IIIF into my Omeka exhibit through a [plugin]( <https://omeka.org/classic/plugins/IiifItems/plug-in). IIIF stands for "International Image Interoperability Framework" and I promise it is more exciting than it sounds. The developers at the University of Toronto created this neat walkthrough and quick tutorial of its attributes:

https://digitaltoolsmss.library.utoronto.ca/

IIIF makes it easy to transcribe, annotate and view images and its associated metadata. I am a little concerned that some of the images I plan to upload might not be high quality enough for IIIF. However, after putting out one massive Omeka fire I am allowing myself to be optimistic about just learning how to implement IIIF. I just need to do the damn thing. 

