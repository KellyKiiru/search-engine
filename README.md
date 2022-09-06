This is a personal project to create a private search engine that doesn't not share user data. 

First, set up linode at "https://cloud.linode.com"

Once your linode is set, paste the SSH KEY into your terminal to get logged in.

At this point, run sudo apt update && sudo apt upgrade to update all linuz packages.

Install docker: sudo apt install docker.io

Install docker-compose that makes it possible to have many docker containers

clone the following repository into the current working folder - git clone https://github.com/searxng/searxng-docker.git