Assignment - Cloudmesh Docker
============================

This is a 6 star project if done and can be pursued as alternative to other homework. However, this may not be an easy project and requires weekly progress reports.

Preriquisite
------------

* Familiar with Docker
* Familiar with python 2.7.11
  
Goal
----

Cloudmesh contains an abstraction layer that allows the integration of other cloud IaaS into cloudmesh. Furthermore, cloudmesh contains a Dockerfile that installs cloudmesh into
a container. The Dockerfile and possibly docker has some limitations.

1. Develop a scure mechanism to use your local ssh keys within the docker container. There  may be multiple solutions for this. Discuss security implications and shortcommings of your solutions. Which one is the best one (you only have to identify one of them and implement the one you find most secure). Discuss this solution with the Gregor and Badi. Can ssh key add be used? Is there a difference when we use OSX, Linux, Windows10?

2. Develop a mechnism to use docker swarm or an alternaete distributed framework to run distributed containers on multiple machines. Prepare an ansible script for the deployment

3. Add a framewwork so the number of containers can be dynamically added or removed (swarm may provide this for you). In that case create unit tests that demonstrate this feature

4. Showcase that you can add machines to your swarm and do a simple analysis. Maybe you need to install something on top of swarm, maybe hadoop?
