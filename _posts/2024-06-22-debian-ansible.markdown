---
layout: post
title:  "DebianAnsible"
date:   2024-06-22 10:34:28 -0400
categories: projects
---



DebianAnsible is a set of scripts and Ansible playbooks that allows me to quickly configure a base Linux system (Arch or Debian) into my customized setup of choice. Through this project I learned about Ansible, an industry-standard tool for configuration management, as well as the importance of managing configurations for production computers.


!["A screenshot of a YAML file containing instructions to move configuration files into particular locations in a Linux system."]({{ site.url }}/assets/DebianAnsiblePhoto.png)
*Here is an example of one of my Ansible playbooks --- this playbook moves my software configurations into their proper locations on a newly installed system.*

Somewhere along my Linux journey I realized that I had a real problem — I kept breaking and reinstalling my OS. While this wasn’t normally an issue, it was a waste of time and I lost some data once after I had to reinstall my OS. Something needed to change.

After seeing [LARBS](https://github.com/LukeSmithxyz/LARBS), a project by a YouTuber to automate installing Arch Linux, I was inspired to create my own setup script for my environment. By this time, I was using i3wm and was managing most of my software configurations through configuration files, so using a version control system made sense. After looking to see what my options could be, I decided to learn how to use Ansible to automate my OS reinstallations. While this didn’t fix my problem of properly backing up data, it did allow me to fine-tune my system configurations so that I had less issues when setting up and maintaining my computers.

The Ansible community is vast and the tool itself is extremely powerful, so it took me some time to accustom myself to it. I wasn’t interested in creating a script that would run on a server, but I needed my Ansible playbook to interface with both the system (moving configuration files to the correct places on my system) and other pieces of software (such as the system’s package manager). After learning the syntax and usage of Ansible, I’ve enjoyed the simplicity of tweaking my setup and having those changes be reproducible.

Configuration management isn’t something that is taught in Computer Science curriculum, but it is an essential skill for production software engineers to know when maintaining large projects. Through my experiments with maintaining a configuration for my personal computers, I’ve gained hands-on experience with the process of creating and maintaining production computer configurations. It’s simplified my life and has made my Linux re-installations less prone to errors. This has helped me focus on being able to use my computer for more practical things than constantly reinstalling my OS of choice.

Be sure to check out [this project on Github](https://github.com/Will-Bo/DebianAnsible) and my other projects on my GitHub account, [Will-Bo](https://github.com/Will-Bo)!
