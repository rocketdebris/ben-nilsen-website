---
title: 'Rationale'
date: 2024-05-02T19:52:28-04:00
draft: false
params:
  author: Ben Nilsen
  toc: true
  description: "My rationale for writing my own note sharing server."
---

## What's the Big Idea?
So, you're thinking, aren't there enough apps out there for taking notes? What
is yours going to do differently to stand out?

Great question!

Four things jump out first about my approach:
1. No vendor locking
4. Data Privacy
2. Plain Text
3. Share Notes with anyone

## No Vendor Lock
It is not my goal to lock you into using my application or ecosystem. It is and
always should be your choice to use whatever tools you want as interoperably as
possible. This notes syncing utility is designed never to lock you in. If you
like it and it helps you, use it! If not, feel free to take your notes (which
belong to you, see below) and try something else that does work for you!

## Data Privacy
Your notes are yours. No one else needs to see or analyze or create advertising
profiles from your stuff. If you choose to self-host, all your data will be on
your own hardware, no external connections or accounts whatsoever. If you 
choose to use the Turso backend for a small fee, you will be assigned your own
database, no accidental data leaks possible. Either option, your notes will be
encrypted end to end and accessible only by you. I will not have access to your
decryption keys.

Remember, if someone is offering you a free product on the internet that costs
money to keep running, YOU'RE THE PRODUCT and your data is for sale.

## Plain Text
Don't get lost in all the flashy features that notetaking apps try to sell you,
plain text is unreasonably effective and can be opened and edited on nearly any
device in existence. Your notes will remain yours and readable (and renderable
if you decide to use Markdown) indefinitely. Keep using your favorite editor,
be that TextEdit, Notepad, SublimeText, Vim, Emacs, Gedit, or whatever else you
have on hand. Your notes will be encoded into your database for syncing and
sharing, but will live on your filesystem on all your devices. Internet down?
No problem. Changes sync after you're back online.

## Sharable Notes
There are a ton of apps out there that sync your files and notes between all
your own devices. But there aren't that many that allow you to share them with
others. Need to be able to have a live updating grocery list while you're
grabbing bread and milk? Need to share one idea from your ideas direcotyr with
a friend or coworker? Not only are notes sharable, but you can also allow
different.
