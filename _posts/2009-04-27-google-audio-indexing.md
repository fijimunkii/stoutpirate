---
layout: post
title: google audio indexing
categories:
- google
tags: []
status: publish
type: post
published: true
meta:
  btc_comment_counts: a:0:{}
  btc_comment_summary: a:1:{i:0;a:3:{s:11:"comment_src";s:7:"twitter";s:3:"cnt";s:1:"1";s:7:"enabled";s:1:"1";}}
  btc_post: a:6:{s:2:"ID";s:3:"174";s:13:"post_date_gmt";s:19:"2009-04-27 22:48:38";s:23:"initial_import_date_gmt";s:19:"2009-05-26
    03:53:01";s:20:"last_import_date_gmt";s:19:"2009-05-27 22:35:21";s:4:"hits";s:1:"1";s:6:"misses";s:2:"39";}
  _edit_lock: '1241215728'
  _edit_last: '1'
---
<strong><i>Update 8-29-2013 </i>-- Google GAudi appears to have been retired and the google group along with it has been expunged!</strong><br /><br />
Google is using speech recognition to index political videos on youtube.  With a search, one can easily find what a politician has to say about a particular subject. <a title="http://labs.google.com/gaudi/" href="http://labs.google.com/gaudi/">http://labs.google.com/gaudi/</a><br /><br />

<!--more-->

Google wants to unleash this powerful tool to index all of youtube's shenanigans, after they've tested it on politics.  I think it will make a major impact on how we access information.<br /><br />

What google says about the technology:
<blockquote>Google Audio Indexing uses speech technology to transform spoken words into text and leverages the Google indexing technology to return the best results to the user.<br /><br />

The returned videos are ranked based -- among other things -- on the spoken content, the metadata, the freshness.
<br /><br />
We periodically crawl the YouTube political channels for new content. As soon as a new video is uploaded to YouTube, it is processed by our system and made available in our index for people to search.</blockquote>
I did some research into what they are actually using to detect the speech patterns.  It is called <a href="http://svr-ftp.eng.cam.ac.uk/comp.speech/Section6/Recognition/htk.html">Hidden Markov Modelling</a>.  Here is a pdf explaining some of the <a href="http://www.hpl.hp.com/techreports/Compaq-DEC/CRL-97-7.pdf">mathematics behind it</a>.
<br /><br />
I would like to share some other documents I came across that I thought were interesting:
<br /><br />
<a href="http://faculty.ksu.edu.sa/YAlohali/Documents/Forms/AllItems.aspx?RootFolder=http%3a%2f%2ffaculty.ksu.edu.sa%2fYAlohali%2fDocuments%2fAccentIdentification&amp;FolderCTID=0x0120003108F2F933FF1F42A8C7BB969AF3407F">This is a 7-part report on how to get Saudi Speech Recognition to differentiate and understand the different accents of their language.</a>
<br /><br />
<a href="http://www.phon.ucl.ac.uk/resource/sfs/howto/htk.htm">How To: Use HTK Hidden Markov modelling toolkit with SFS</a>
<br /><br />
<a href="http://groups.google.com/group/google-audio-indexing/">The Google Group for Google Audio Indexing</a>
