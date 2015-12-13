# QuickNode
Heroku HTML Hosting Tempate

clone repository
$ git clone https://github.com/EN10/QuickNode.git

download the toolbelt
$ wget -O- https://toolbelt.heroku.com/install-ubuntu.sh | sh

login to heroku
$ heroku login

deploy app
$ cd QuickNode/
$ heroku git:remote -a QuickNode
$ git add .
$ git commit -am "make it better"
$ git push heroku master
