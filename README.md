# jenkins-controller-agent-dockerized

This repo contains 3 scripts you can use for Dockerize Jenkins controller and agent.
The set up is done on ubunutu 
The jenkins-teardonw script removes all docker volumes, networks, and containers in your machine. So, if you have volumes, networks and/or containers that you want to keep that please do not execute that script. I used to it in my machine to start from stratch.
The jenkins-setup script, creates a dockerized jenkins controller and dockerized jenkins agent while providing all the pieces of information you need to make jenkins controller UI configuration (see the video )
The jenkins-setup-agent create a dockerized jenkins agent.
