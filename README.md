# Dockerizing-Selenium-Scripts-in-Python.
One of the leading causes of “Im-pos-tor Syn-drome” among developers is not knowing Docker. It makes it harder to go to parties where everybody is talking about Kubernetes, Swarms, Shuffle Sharding, while, you hide in the corner googling “what is a container”, we’ve all been there at one point or another. In this article, you’ll learn the basics of docker to survive as a developer in 2023.

We’ll take a hands-on approach by containerizing a Python web-scraping script. I’ll assume you’re new to this so, we’ll go and look at the fundamental instructions in a dockerfile, in addition, we’ll learn how to build an image and run a container using that image.
What is docker?

You might have heard the term “Docker” being thrown here and there, let’s define it a bit. Wikipedia defines Docker as:

an open-source project that automates the deployment of software applications inside containers by providing an additional layer of abstraction and automation of OS-level virtualization on Linux.

Wow! that’s a mouthful. To simplify, Docker is a tool that simplifies the deployment of applications on a Linux operating system. It uses containers as a sandbox for running applications, which helps to streamline the process. By packaging applications and their dependencies into a standardized unit, Docker makes software development more efficient. Unlike virtual machines, containers don’t have high overhead, which means they use system resources more efficiently

Containers and Images

A container is an instance of a Docker image. An image is a read-only template that contains all the instructions and dependencies needed to run a particular application. It’s like a snapshot of a container at a particular point in time.

To create a container, you start with an image and add a writable layer on top of it, which allows you to modify the contents of the container without changing the underlying image. Multiple containers can be created from the same image, and each container can be customized to meet the specific needs of the application or service it hosts.

Want to learn more? Head over to my blog https://medium.com/@moiz2050_27618/dockerizing-selenium-scripts-in-python-3a937f0517bb
