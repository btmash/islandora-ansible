# README

---------------------------------

The purpose of the project is to have a way to install Islandora via Ansible.
I have provided a Vagrantfile so you can also install locally via Virtualbox and Vagrant.
Currently, everything *but* the actual islandora (drupal) part of the setup is working (ie. MySQL, Fedora Commons, Freelib-Djatoka, Solr, etc. are all working). I need to create a drush make file to download the dependencies and then this will be ready to go. If someone wants to help on this, help is welcomed!

## Why not chef?

Ryerson Libraries has a chef installer for Islandora already and it is on [Github](https://github.com/ryersonlibrary/islandora_chef). With that said, I really like Ansible since it is really easy to understand. There are also very few dependencies (no additional libraries required on provisioned server since provisioning works via ssh).

## What do I need?

You need Ansible installed - see http://docs.ansible.com/intro_installation.html.
