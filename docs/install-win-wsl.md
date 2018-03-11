description: Read how to install and configure Bastion Bot, on Windows Subsystem for Linux. One step closer to making your Discord Server AWESOME!

# Bastion Installation on Windows Subsystem for Linux

*If you are going to install Bastion in any other operating system besides Windows,
you can skip this step and visit to the appropriate page for the specific guides
on [macOS](install-macos) or [Linux](install-linux). Or if you are an advanced
user and want to know what's going on with the installer or want to go through
the installation step by step, manually (trust me I understand), we have a
[manual installation guide](install-manual), made just for you!*

!!! tip "Want to run Bastion 24x7?"
    If you want Bastion to serve 24/7 without having to hosting it on your
    PC and want to keep it cheap, reliable and convenient as possible, you can
    install Bastion, using the [linux guide](install-linux/), on a [DigitalOcean](https://m.do.co/c/0ee6cb9c7ee0)
    Linux VPS using [this link](https://m.do.co/c/0ee6cb9c7ee0) (using this link
    will be supporting The Bastion Bot project and will give you **$10** for
    free to start with DigitalOcean).

## What is Windows Subsystem for Linux?

The Windows Subsystem for Linux lets developers run Linux environments --
including most command-line tools, utilities, and applications -- directly on
Windows, unmodified, without the overhead of a virtual machine.


You can:

  1.  Choose your favorite Linux distributions from the Windows Store.
  2.  Run common command-line utilities such as grep, sed, awk, etc.
  3.  Run Bash shell scripts and Linux command-line applications including:
      * Tools: vim, emacs, tmux
      * Languages: JavaScript/Node.js, Ruby, Python, C/C++, C# & F#, Rust, Go,
        etc.
      * Services: sshd, MySQL, Apache, lighttpd
  4.  Install additional Linux tools using the distribution's built in package
      manager (apt-get, for example).
  5.  Invoke Windows applications from the Linux console.
  6.  Invoke Linux applications on Windows.

## Install Windows Subsystem for Linux

If you're on **Windows 10**, follow [this guide](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
from Microsoft to install Windows Subsystem for Linux:
```
https://docs.microsoft.com/en-us/windows/wsl/install-win10
```

Or if you're on **Windows Server**, follow [this guide](https://docs.microsoft.com/en-us/windows/wsl/install-on-server)
from Microsoft to install Windows Subsystem for Linux:
```
https://docs.microsoft.com/en-us/windows/wsl/install-on-server
```

## Install Bastion
Now that you've installed Windows Subsystem for Linux, you've a Linux
environment inside Windows. All you need to do now is follow the [Linux guide](install-linux)
on installing Bastion.
