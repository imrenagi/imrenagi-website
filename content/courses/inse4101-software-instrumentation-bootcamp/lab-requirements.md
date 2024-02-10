---
author: "Imre Nagi"
title: "Lab requirements"
description: "This course requires you to have an Ubuntu VM and several software installed on it. You must have it ready before the first session"
tags: ["bootcamp", "software-instrumentation"]
date: 2024-02-09T00:00:00+07:00
thumbnail: ""
---

## Getting Ubuntu VM

This course is developed and tested on **Ubuntu 22.04** LTS (x86 architecture). So, I **really** recommend you to use **Linux** based operating system for this course. But, if you are using other Linux distro, I probably won't be able to help you if you encounter any issues because of my skill issue, but I believe ChatGPT might!

### Ubuntu VM on cloud

This course will require you to run many containers. So, I recommend you to have at least 8GB of RAM and 4 vCPU. If you have more budget, you can rent a bigger VM for your convenience.

The easiest way to get an Ubuntu VM is actually by rent one from any cloud hosting/provider. There are several options that you can choose from:

* [Digital Ocean](https://www.digitalocean.com/)
* [OVH](https://www.ovhcloud.com/)
* [Contabo](https://contabo.com/)
* [Linode](https://www.linode.com/)
* [Google Cloud](https://cloud.google.com/)
* [AWS](https://aws.amazon.com/)

I'm currently using Contabo VPS XL (10 vCPU, 64GB RAM, 1.6TB SSD) for my workstation and it works well for me for developing this course and run some experiments. It is also relatively cheap (around 40USD/month) compared to other hosting/cloud provider. (I'm not endorsing Contabo anyway :p)

### Ubuntu VM on your laptop

If you don't want to rent a VM, you may also install Ubuntu on your laptop. But, I don't recommend this option because it will be a lot of hassle to install and configure everything. Especially if you are using recent Macbook Pro with Apple M1, M2, or M3 chip. 

If you want to use any software virtualization, there are several options that you can choose from:

1. [Canonical Multipass](https://multipass.run/)

    This is relatively new for me. I'm still experimenting with this. If you are using Macbook Pro with Apple M1, M2, or M3 chip, this is probably the best option for you so far.

1. [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/)

    I used to use Vagrant for teaching internal DevOps bootcamp in my company. But, the experience is really bad thus I don't recommend this option. Especially if you are not familiar with this and you are using Apple M1, M2, or M3 chip. Rent a VM instead!

Unfortunately, this course won't discuss much details about how to configure it so that you can access the application running inside the VM from your host machine (e.g. port-forwarding, networking, etc.). But, you can always ask me if you encounter any issues. I might not have solution, but I might be able to help you to find the solution.

### Using Windows

**DON'T!** 

Just kidding. I'm not familiar with Windows. The last Windows OS I used was Windows Vista. So I won't be able to help you if you encounter any issues. But, if you want to use Windows, you can use WSL2. I haven't tried it myself, but I heard it works well. 

## Software requirements

Here is the list of software that you need to install on your Ubuntu VM:

1. [Install Go 1.21.x](https://golang.org/doc/install)

1. [Install python on Ubuntu 22.04](https://www.linuxcapable.com/how-to-install-python-3-10-on-ubuntu-linux/)

1. [Install Docker on Ubuntu 22.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-22-04)

1. [Install Docker Compose on Ubuntu 22.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-22-04)

## Supplementary learning resource

###  Docker

If you are not familiar with Docker, I have few live streaming recording discussing about Docker. But this is only available in Indonesia language. You can watch it here:

* [Mengenal Container dan Docker Sampai Jago Dalam 2 Jam](https://www.youtube.com/watch?v=26O6Ke03j3Y&t=1278s&pp=ygUQaW1yZSBuYWdpIGRvY2tlcg%3D%3D)
* [Pengembangan Microservice Dengan Docker Compose](https://www.youtube.com/watch?v=ALGVV5cGUtc&t=2115s&pp=ygUQaW1yZSBuYWdpIGRvY2tlcg%3D%3D)