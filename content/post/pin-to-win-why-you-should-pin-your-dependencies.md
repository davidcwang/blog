---
title: "Pin to Win: Why you should pin your dependencies"
date: 2019-08-11T17:50:44-07:00
tags:
    - Pip
    - Pyenv
    - Pyenv-virtualenv
    - Python
    - Version-Pinning
draft: false
---

In the age of containers and CI/CD pipelines, repeatable and consistent builds have become more and more critical. A key part of having consistent builds is ensuring that you have a consistent environment and consistent dependencies - while the former can be achieved by using Docker, the latter can be achieved by explicitly pinning your dependencies.

If you’re developing a Python application, most likely you’ll be using pip to manage your dependencies. In pip, you list your dependencies in a requirements.txt file and run “pip install -r requirements.txt” to install your dependencies. In this blog we’ll be going over how to use tools like pip, Pyenv, and Pyenv-virtualenv to manage the dependencies for your project. 