Story
======

As a CMG manager, I want to see how you code a game of Tic Tac Toe, so that I can get a feel for a candidate's skills and strengths.

Acceptance criteria
=======================

* The AI should never lose
* The submission must include both server & client side code -- no CLI-only or browser-only implementations. Play to your strengths, but show us your full range of skills.
* Quality counts! A good submission that takes a while is better than a poor submission quickly.
* You should include clear instructions for how to run your application


Technical notes
------------------

* We are a Django shop, but it is not a requirement that you implement your program as a Django app.
* Make sure your submission accurately reflects your development style.
* Commit early and often, with good messages.


Submissions
---------------

1. Publicly: Fork this repo and send us a pull request.
2. Privately: Send us a tar.gz of your solution **including your .git folder** so we can see your commit history.

Developer Notes:
-----------------

This is a sinatra app written under Ruby 1.9.3

* Install sinatra $gem install sinatra : require in app file that starts the program
	enable sessions after require (enable :sessions)
* Adde files for Passenger since that's what runs on my VPS
* Install rspec and run rspec --init
* localdev install shotgun so you don't have to restart Sinatra at every code change:
	$gem install shotgun
	$shotgun -p 4567 app.rb
* initial game will always have client move first. As tic-tac-toe goes this gives the upper hand and this exercise does not allow turn switching.

