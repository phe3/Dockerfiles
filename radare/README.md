# Radare + Yara

[![Build Status](https://travis-ci.org/geerlingguy/drupal-honeypot.svg?branch=8.x-1.x)](https://travis-ci.org/geerlingguy/drupal-honeypot)


## About

Lightweight Alpine image with radare and yara installed on top;
Fast and easy option for RE Linux binaries, create and test yara rules.

## Configuration

This image doesn't require any additional configuration, just make sure of sharing the directory where you 
Have the binaries within the container when run it.

Eg:

	docker run --rm -it -v ~/workdir:/home/user/workdir phee13/git-autobuilt:radare


## Use in Your Own Forms

Free to use, modify and adapt.

## Credit

Heavily based on the remnux project;
Just a up to date and lighter implementation of it.

https://github.com/REMnux/docker/tree/master/radare2
