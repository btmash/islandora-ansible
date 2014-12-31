# README

---------------------------------

The purpose of the project is to have a way to install Islandora via Ansible.
I have provided a Vagrantfile so you can also install locally via Virtualbox and Vagrant.

## Why not chef?

Ryerson Libraries has a chef installer for Islandora already and it is on [Github](https://github.com/ryersonlibrary/islandora_chef). With that said, I really like Ansible since it is really easy to understand. There are also very few dependencies (no additional libraries required on provisioned server since provisioning works via ssh).

## What do I need?

You need Ansible installed - see http://docs.ansible.com/intro_installation.html.
