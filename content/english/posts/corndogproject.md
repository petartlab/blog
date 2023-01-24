---
title: Corndog Project
author: PetArtLab
date: 2023-01-24
draft: false
description: app to tell you whether corn present on dog paw
tags:
 - greyhound
 - paws
 - corns
 - limping
 - lame dog
categories:
 - healthcare
thumbnail: "images/corn.jpg"
---

We are working on a tool to help people determine whether a corn is present in their dog's paw. We might encourage voluntary donation to greyhound charities but it will be for free to everyone. 
<br>
You can try it out here: [Corndog App](https://huggingface.co/spaces/com48com/corndog). The app seems faster if follow the link compared to using the tool below.

## **Photo Collection** ##
It would be great if you could email us photos of your dog's paws to add to our album to improve our model. Both photos of paws with corns and without corns are helpful! 

<blockquote class="imgur-embed-pub" lang="en" data-id="a/pePHeVW"  ><a href="//imgur.com/a/pePHeVW">corn</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

<blockquote class="imgur-embed-pub" lang="en" data-id="a/qnjbkBg"><a href="//imgur.com/a/qnjbkBg">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>
<br>
## **Corndog App** ##

Drop in your photo here to check whether your dog has a corn! Please keep in mind the model is still learning and cannot definitively tell you whether your dog has a corn. For medical advice, please consult a vet.

<script
	type="module"
	src="https://gradio.s3-us-west-2.amazonaws.com/3.4/gradio.js"
></script>

<gradio-app src="https://com48com-corndog.hf.space"></gradio-app>
