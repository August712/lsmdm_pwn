## LSMDM_pwn: A program to remove MDM on an idevice. [![Build Status](https://travis-ci.org/August712/lsmdm_pwn.svg?branch=master)](https://travis-ci.org/August712/lsmdm_pwn)

> - Pwn (Verb)

> Derived from the word "own" meaning "to make higher than another, to dominate"

> 1. The act of dominating something.

> 2. Great, ingenious; applied to methods and objects.

It’s about time I pull this project out of the ashes.

“LSMDM_pwn” removes Mobile Device Management (MDM) services from an iOS device. Since my school used LightSpeed MDM Services (LSMDM) to tower over us all, I thought I would make the name a joke. LSMDM_pwn uses a modified partial restore containing the ~/MobileConfiguration/ directory.

Now with iOS mitigating backup modifications as of iOS 10, I gotta find a new way to get this to work.

**WARNING! THIS BETA REQUIRES A MAC WITH XCODE 7.0+ INSTALLED!**



### Install

`git clone https://github.com/August712/lsmdm_pwn.git && cd lsmdm_pwn && lsmdm_pwn.sh`

or

Download the zip and `cd /wherever/the/fuck && lsmdm_pwn.sh`

-----

Developed by @August712
