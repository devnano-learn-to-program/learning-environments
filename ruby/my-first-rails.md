Install Guest Addition - => Devices => Install Guest Additions

My First Rails App

~gem install rails
~ mkdir code
~ cd code
~ rails new my_first_app —database=postgresql
~ cd my_first_app
~ bundle install
~ bundle exec rails server
~ open Firefox - go to http://localhost:3000

~ Lesson on Model View Controller and rendering dynamic content

~ Open Project in Atom /home/<username/code/my_first_app

~git init
~git add -A
~git commit -am "Initial Commit"

HEROKU
Sign up for heroic
Login to Heroku and Create a new App called <name>-my-first-app
Install Heroku Command Line Tools
~wget -qO- https://cli-assets.heroku.com/install-ubuntu.sh | sh
~heroku auth:login
~heroku git:remote -a brettallred-my-first-app
~heroku open
~heroku keys:add
~git push heroku master
~heroku open

GITHUB
Create a Github Account
Create a new repository for your code
Add SSH Key (Profile Icon, Settings, SSH)
Add new SSH Key
~cat ~/.ssh/id_rsa.pub
Paste and Save your SSH Key

CREATE index.html in atom

GIT WORKFLOW
~git status
~git add -A
~git commit -am "MESSAGE HERE"
~git push heroku master 
~git push origin master