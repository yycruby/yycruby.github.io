---
layout: page
title: Ruby Warrior Install Notes!
tagline: 23/04/13
---
{% include JB/setup %}


Hi everyone! In preparation for tomorrow night I thought I'd post some notes on how to setup machines beforehand so we can get straight down to business tomorrow.

Please make sure you have at least ruby-1.9.3 installed on your machine. That should be it.


###Mac
	# if you do not have homebrew installed, taken from homebrew.sh
	ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"

	#install git
	brew install git

	#install XCode from mac AppStore... 

	#install rvm if you wish
	curl -L https://get.rvm.io | bash -s stable

	#reload shell
	source ~/.rvm/scripts/rvm

	#double-check rvm installation
	type rvm | head -n 1 

	#should output rvm is a function
	#else follow instructions here https://rvm.io/rvm/install/

	#double check system requirements
	rvm requirements

	# use new ruby
	rvm use 2.0.0

	# install rubywarrior
	gem install rubywarrior

	#run setup
	rubywarrior

	#follow prompts

###Ubuntu
Truncated for brewvity, largely the same as above, and I assume if you're running Linux you know how to install package using apt-get

	sudo apt-get install gitcore
	curl -L https://get.rvm.io | bash -s stable
	source ~/.rvm/scripts/rvm


	#reload shell
	source ~/.rvm/scripts/rvm

	#double-check rvm installation
	type rvm | head -n 1 

	#should output rvm is a function
	#else follow instructions here https://rvm.io/rvm/install/

	#double check system requirements
	rvm requirements
	#install any missing dependencies
	rvm use 2.0.0

	# install rubywarrior
	gem install rubywarrior

	#run setup
	rubywarrior

	#follow prompts

###Windows

Fair Warning! I seriously had to look this up, should be correct but I cant guarantee anything.

	#download http://rubyinstaller.org/downloads/
	#get ruby 2.0-p0, because new stuff is fun

	#install your git client of choice!
	# I'm assuming people still use TortoiseGit?
	# or use the fancy github windows client http://windows.github.com/



Thanks all, see you tomorrow night!!!

[Ben](http://twitter.com/bennett_stevens)



Past Meetups

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


