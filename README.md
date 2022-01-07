# KubeNodeDescriber5000

![KUBENODEDESCRIBER5000](mediafiles/kubenodedescriber5000.jpg)

# Table of contents

  1. [Introduction](#introduction)
  2. [Prerequisites](#prerequisites)
  3. [How to install?](#how-to-install)
  4. [Example](#example)

# Introduction

Hi, I'm Joris and I'm sick and tired of looking up my node name. That's why 
I created this project.

I know, there are a lot of other tools on the "OpenSource Market" but this one 
just does what it needs to do, no further bullshit. 

# Prerequisites 

Have a working kubernetes cluster with nodes.

# How to install? 

Well that is pretty simple. 

* Clone this git 
* Put the KCS9 file in your `/usr/local/bin` folder
* Edit the permissions on the file `chmod +x /usr/local/bin/KND5`
* `exec $SHELL` (Optional step, re-opening your terminal will do the trick as well) 
* You will be able to use `KND5` as a command from now on
# Example 

        user@ubuntu:~# KND5
        1) minikube 
        Which node do you want to describe? 
        Name:               minikube
        Roles:              master
        Labels:             beta.kubernetes.io/arch=amd64
                            beta.kubernetes.io/os=linux
        ... 