description: Read how to install and configure Bastion Bot, on macOS. One step closer to making your Discord Server AWESOME!

# Bastion Installation on macOS

*If you are going to install Bastion in any other operating system besides macOS,
you can skip this step and visit to the appropriate page for the specific guides
on [Windows](install-win) or [Linux](install-linux). Or if you are an advanced
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

Run the following command to download the Bastion Bot installer that'll help
you install Bastion smooth and easy:
```bash
curl -sL https://raw.githubusercontent.com/TheBastionBot/Bastion-Scripts/master/BastionInstaller_macOS.sh -o BastionInstaller.sh && chmod +x BastionInstaller.sh
```

## Proceed with the installation

Now that you've downloaded the installer, it will automatically download and
install everything you'll need to run Bastion.

To start the installation, run the following command:
```bash
./BastionInstaller.sh
```

Wait for a few moments for the installer to finish installing.

If everything was successful, it'll let you know that the installation
was successfully completed and Bastion is ready to boot up. :smile:

Now, you should have a new folder named `Bastion` in your `$HOME` (`~`)
directory.

## Configure Bastion
Here comes the last (but not the least) step, configuring Bastion, before it's
first run.

1.  Go to the `settings` directory (folder), that's inside the `Bastion` folder.
2.  You'll see two files here, `credentials.json` and `config.json`.
3.  Edit the `credentials.json` and `config.json` files and make the changes as
    required and save the file.

## Get Bastion running

You get a `bastion.sh` script file that makes it easy to run Bastion without
any hassle, among other things. To start Bastion, run the following command:
```bash
cd ~/Bastion # Changes the current directory to the `Bastion`, if you aren't already there.
./bastion.sh --start # Starts Bastion
```

!!! tip "Pro Tip"
    The `bastion.sh` script can do a whole lot of other things besides just
    helping you with running & updating Bastion. Want to find out what else
    can it do? Just run the following command to know more: `./bastion.sh`
