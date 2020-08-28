---
layout: page
title: Setup
root: .
---


### Key requirement

The main requirement for this workshop is a personal computer with a web browser and a command line shell program.  

*Windows* users: [MobaXterm](https://mobaxterm.mobatek.net/download-home-edition.html) is the **preferred option**, as it also provides X11 forwarding.  The *Portable Edition* is best, as it does not require administrative privileges.  
<!--Other acceptable options would be [Visual Studio Code](https://code.visualstudio.com/) or PuTTY, but you will also need to install [Cygwin/X](https://x.cygwin.com) to run the example on X11 applications.  -->
In this way you will be able to follow the online materials and to login to a facility with the required software stack.


### Self-paced: Pawsey users

* **Nimbus Cloud @Pawsey**: if you have access, both Singularity and Docker are preinstalled in the *Ubuntu Pawsey* base image.
<!-- Test: Ubuntu 18.04 VM with 2 cores, 6 GB RAM, 40 GB disk -->

* **Zeus @Pawsey**: if you have access, Singularity can be loaded with `module load singularity`. 


> ## Advanced self-paced: installation DIY (Do It Yourself)
> 
> If you have your own machine, you can install the required software yourself (might take a while).  
> Note that you will need ***admin* privileges** in the machine to finalise the installation.
> 
> #### Linux box
> 
> Required packages:
> - Singularity : [script]({{ page.root }}/files/install-singularity.sh) \| [docs](https://sylabs.io/guides/3.5/user-guide/quick_start.html)
> - Docker : [script]({{ page.root }}/files/install-docker.sh) \| [docs (unofficial)](https://www.itzgeek.com/how-tos/linux/ubuntu-how-tos/how-to-install-docker-on-ubuntu-18-04-lts-bionic-beaver.html)
> 
> **Note:** install scripts have been tested on a Ubuntu machine through a user that can run *sudo* commands without password prompts. There's no warranty they will work in your Linux box, you should consider them as templates.
> 
> #### macOS or Windows machine
> 
> For *Singularity*, you will need to setup a Linux virtual machine, and then follow the same instructions as above.  
> It's not as bad as it sounds... the main two options are:
>   - Vagrant: follow these instructions by Sylabs on [Setting up Singularity with Vagrant](https://sylabs.io/guides/3.5/admin-guide/installation.html#installation-on-windows-or-mac) (*macOS* users: DO NOT use the proposed *Singularity Desktop*, use Vagrant instead);
>   - Multipass: follow instructions from the [Multipass Homepage](https://multipass.run).
> 
> For *Docker*, you can download and run installers for [macOS](https://hub.docker.com/editions/community/docker-ce-desktop-mac/) and [Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows/).
{: .challenge}
