---
title: PocketSpruce
kind: article
created_at: 2013-11-25
---

To have a deeper understanding on Ruby, I decided to start a project to scratch my own itch. 

I have been using Pocket for a while already, and collected many links, maybe even too many. I wanted a simple service which can email a daily random article from my list to my mailbox. Also, since there are many duplicate links and dead links in my list, I wanted the service to clean them up too.  

<!-- more -->

Introducing [PocketSpruce](http://www.sprucekit.com). 

A simple web service which does the above. Currently, the main function is to email an item from the user's Pocket list and archive it. So far it works well and it uses the below external services.

* Pocket API
* Mandrill to set transactional emails
* Readability API to extract out the content of the article to be sent to the user. 

Code is up on GitHub but still pretty raw and lots of code clean-up to be done. First thing first is to add a testing framework, maybe RSpec. Try it out and do drop me a feedback. Stay tuned for more updates.
