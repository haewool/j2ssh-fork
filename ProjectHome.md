## This project has moved to GitHub - https://github.com/UniversityofWarwick/j2ssh-fork ##




## If you want a decent Java SFTP Server, please go and look at the [Apache MINA SSHD server](http://mina.apache.org/sshd/) instead. This project will probably only bring grief and sadness. ##

### Future ###

Now that this is working basically to do what we want, there probably won't be any further work on it. If you are looking for a well-built and fully featured SSH server in Java, you would be better off waiting for the Apache MINA [SSHD server](http://mina.apache.org/sshd/) to bear fruit.

### About ###

This is a fork of the J2SSH library, mostly unchanged in terms of the SSH support, but with some tweaks, changes and bugfixes as required. There were also some important configuration files missing in the original, which I have managed to piece together by looking at the source.

This version is being compiled for Java 5.

The original project is linked to the right.

There probably won't be much work on the default filesystem class since the developers are implementing one specific to an internal application. So bugs in the provided native filesystem class may not get fixed. It does, however, mostly work as is.