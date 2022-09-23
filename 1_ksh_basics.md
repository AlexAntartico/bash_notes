# KSH basics and simple guidelines

**Why KSH and not Bash?** you may ask yourself. Well, turns out KSH is an actual POSIX IEEE compliant standard and we all should care about this. Lots of acronyms in that last sentence. Allow me to clarify som of these:

- **KSH** stands for Korn Shell, created by David G. Korn while he was working at AT&T Bell Laboratories and AT&T Research; considered an iteration of the original unix shell. We will focus specifically in [KSH93u+m](https://github.com/ksh93/ksh), which is no longer developed by AT&T but it's still very much alive. KSH has the capacity of executing a file or interactively executing commands from a terminal.
- **POSIX** stands for Portable Operating System Interface, this standard makes possible compatibility at a source code level. Supose you have written a ksh script in your favorite linux distro, thanks to the POSIX standard; you will be able to run in a modern macOS machine without having to make major (if at all) modifications. now, try running the same script in Windowns and any system call like file navigation, process control, device control will not work. Thanks to The Open Group, a free copy of the latest technical standard can be found [here](https://pubs.opengroup.org/onlinepubs/9699919799/).
- **IEEE** stands for Institute of Electrical and Electronic Engineers and it's pronounced as 'Eye-triple E' it is best known for publishing and certifying most of the standards that rule technology.


## A typical ksh script looks like this

As a developer, sys admin, SRE or whatever your current line of business is; it's very likely you did not receive any formal-ish training in shell and you probably picked this up doing small scripts, gooogling, asking your peers or reading some articles. 



Tasks:
View this Video to beter understand POSIX
https://www.youtube.com/watch?v=728Eu5RFoTs&ab_channel=BrodieRobertson


### Resources:

Description|Link
---|---
Github ksh93u+m repo|https://github.com/ksh93/ksh
POSIX Compliance Explained|https://www.youtube.com/watch?v=728Eu5RFoTs&ab_channel=BrodieRobertson
POSIX entry at Wikipedia|https://en.wikipedia.org/wiki/POSIX

