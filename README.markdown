# sschan

"sschan" is a small Ruby on Rails-based imageboard that I wrote for my friends to post on. An imageboard is an online image-based forum, usually with anonymous posting options and with a distinctive layout style. A good example of an imageboard is: http://boards.4chan.org/v/.

My motivation for making the website stemmed mostly from the fact that imageboard resources do not really exist for Ruby on Rails. It's very easy to make an imageboard using PHP resources, but I wanted to develop one using Ruby on Rails. The process ended up being very interesting and left me with a very usable imageboard website written in my favorite web development framework. Features supported on sschan.org include:

* User profiles with Rails Devise
* Anonymous posting options
* File uploading (including image files, mp3, etc, courtesy of my out-of-pocket Amazon AWS account)
* Post tagging
* Private messaging with Pusher (currently broken after Rails upgrade)
* Other cool things that I forgot to mention, probably

Registration on sschan.org is currently closed, but these screenshots show what the interface looks like from my admin account: http://imgur.com/a/zfi8C