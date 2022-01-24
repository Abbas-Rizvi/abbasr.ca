---
title: Website goal and setup
tags:
- Server
- Hugo

date: 2022-12-01

slug: first
description: What this website is for and how its setup
---

## What this website is for

I've talked about it a little in my about page but I wanted to elaborate a
little bit more on what I actually am trying to accomplish through this site.

Essentially I created this site for three main reasons:

### Reason 1) Project Portfolio

While github is useful for showing projects and code with readme files, I felt
that it would also be good to have them all up in another place aswell for more
ease of reading and possibly online hosting.

### Reason 2) Hosting own services

Another big reason in creating a website is to host my own services. I've
always wanted to do alot more on the internet than just browse and I felt this
was a good step in becoming more independent on the internet.

I wanted to minimize my use of propietery software and "other peoples" services
and creaing a website acts as a portal to allow me to host and access things
I'm interested in like a small blog, git server, file server and even email.
Hosting these things gives me much more control over the way I interact with
these things and provides an open sandbox for expanding.

This brings us to the third reason:

### Reason 3) Post my own content

As someone who is interested in technology I have frequently come across other
peoples websites online where they share opinions, guides and just general
advice regarding different software. While I'm not at that point yet, I want to
do my own part in this eco-system and talk about things I've came across and
learned through working on different things.

## Site Infrastructure

### Website Design

After going through several previous renditions of a website on my own, I
decided to give a Static-Site Generator a try and thus used
[Hugo](https://gohugo.io/) for the creation of the site. I found that Hugo
provided a good balance between providing the user freedom over the design
while still being very convenient and deploying pages statically.

I was able to download a minimal theme and alter a couple of things to create a
website I am happy with. Additionally, I can also easily add new pages through
creating simple markdown files and have them render as static content pages.
These are also put into a list on the category page making blog posts easy to
create.

While other alternatives exist, I am confident that Hugo was a great choice in
the creation of the website.

### Server

Since I wanted to do a little bit more with different services than just a
basic html site, I decided to host the site myself on a VPS. 

I think found that this was a great choice as I was able to improve my Linux
skills working with a headless server, while also familliarizing myself with
how deployment works on servers (at a basic level). Through hosting the site I
learned about [nginx](https://nginx.org/en/), something I plan on using for any
other sites I create in the future.

Although this VPS solution does work, I want to move over to a fully
self-hosted solution so I can create a file server without dealing with any
bandwith limits.
