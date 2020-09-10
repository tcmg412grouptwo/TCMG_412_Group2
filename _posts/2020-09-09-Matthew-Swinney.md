---
layout: post
title: Docker Containerization 
---

A  Docker container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and 

The main advantage of this approach is that both developers and system administrators use the same tool — Docker. Developers create Docker images from Dockerfiles at the development stage, on local computers, and run them in a development environment.

The same Docker images are used by system administrators who make updates to the stage and production environments using Docker. It is very important that Docker containers are not patched when updating to a new version of a software. This means that a new version of your software is represented by a new Docker image and a new copy of the Docker container, but not to patch the old Docker container.

As a result, you can make immutable dev, staging, and production environments. There are several benefits of using this approach. First of all, there is a high level of control over all changes, because changes are made using immutable Docker images and containers. You can roll back to the previous version at any moment. Development, staging, and production environments become more similar to each other than with Ansible. Using Docker, you can guarantee that if a feature works in the development environment, it will work in staging and production, too.settings.


![Docker](https://blog.xebialabs.com/wp-content/uploads/2019/05/docker-e1558536954364.jpg)
