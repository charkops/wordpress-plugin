# Local Development Environment for WordPress plugin

* Requirements:
  * Docker
  * Docker-compose

* This is currently being used to test: https://github.com/charkops/ckops_ads
* The abovementioned plugin is a submodule of current directory

# Getting started

* git clone --recursive https://github.com/charkops/wordpress-plugin
* cd wordpress-plugin
* docker-compose up -d

* Use any browser to browse to: http://127.0.0.3
* You will be prompted to install wordpress if this is your first time, do so
* Go to plugins -> activate the plugin you are testing
* In this case activate the "ckops_ads" plugin
* Go back to http://127.0.0.3 
* You should see ads after every 2nd paragraph of every post.
* profit ???
