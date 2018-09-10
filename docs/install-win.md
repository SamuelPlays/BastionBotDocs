description: Read how to install and configure Bastion Bot, on Windows. One step closer to making your Discord Server AWESOME!

# Bastion Installation on Windows

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

## Download the installer

[Right Click here](https://raw.githubusercontent.com/TheBastionBot/Bastion-Scripts/master/BastionInstaller.cmd)
and Click **Save Link As...** and Save the file as `BastionInstaller.cmd`
(Bastion Installer for Windows).

## Proceed with the installation

Now that you've downloaded the installer, it will automatically download and
install everything you'll need to run Bastion.

To start the installation, **Right-Click** the downloaded file and Click
**Run as Administrator**.

Wait for a few moments for the installer to finish installing.

If everything was successful, it'll let you know that the installation
was successfully completed and Bastion is ready to boot up. :smile:

Now, you should have a new folder named `Bastion` in your User Directory
(`%USERPROFILE%` or `C:\Users\<User Name>`).

## Configure Bastion
Here comes the last (but not the least) step, configuring Bastion, before it's
first run.

1.  Go to the `settings` directory (folder), that's inside the `Bastion` folder.
2.  You'll see two files here, `credentials.json` and `config.json`.
3.  Edit the `credentials.json` and `config.json` files and make the changes as
    required and save the file.

!!! note
    Please don't use the **Notepad** application that
    comes with Windows by default, because Notepad doesn't support the `LF`
    line endings and breaks the file. At least, use a code editor like
    **[Notepad++](https://notepad-plus-plus.org/ 'Notepad++ - Free source code editor and Notepad replacement.')**
    or **[Atom](https://atom.io/ 'Atom - A Hackable text editor for the 21st century.')**.

## Get Bastion running

You get a `run.cmd` script file that makes it easy to run Bastion without
any hassle. To start Bastion, **Double-Click** the `run.cmd` file.

Now, you will see the status of Bastion in a Command Prompt (CMD) window.
If you want to terminate & stop Bastion, just close the Command Prompt window.
