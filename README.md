docker-jenkins
==============

Jenkins in a Docker container; based on Ubuntu 14.04. It comes with the
following plugins:

 * hipchat.hpi
 * greenballs.hpi
 * credentials.hpi
 * ssh-credentials.hpi
 * ssh-agent.hpi
 * git-client.hpi
 * git.hpi
 * github.hpi
 * github-api.hpi
 * ghprb.hpi
 * github-oauth.hpi
 * scm-api.hpi
 * postbuild-task.hpi

Usage
-----

    docker run -d -t birkand/jenkins

Building
--------

Grab Dockerfile from this repository on Github

    docker build github.com/birkand/docker-jenkins

Get a Docker image from Docker index

    docker pull birkand/jenkins


