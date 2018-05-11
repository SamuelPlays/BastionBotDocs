description: Read how to update Bastion, when new updates are available.

# Updating Bastion

When new version of Bastion is released, it brings new features, improvements
and bug fixes. So, you should always try to have the latest version of Bastion,
so you can experience it's all new features and improvements.

To know when new releases are done, have an eye out on the [#announcements](https://discord.gg/fzx8fkt)
channel of [The Bastion Bot: Discord Server](https://discord.gg/fzx8fkt).

!!! note
    Before updating your Bastion Bot, shutdown your bot using the `shutdown`
    command in Discord.

## Updating Bastion on Linux/macOS

Go to your `Bastion` directory. If you haven't changed the default installation
directory and path, run the following command:
```bash
cd ~/Bastion
```

Now that you're in the directory where Bastion is installed, running the
following command will update Bastion and all of it's dependencies to the latest
version:

```bash
./bastion.sh --update
```

Wait for a few moments for the updater to finish updating.

After the updater has updated Bastion, it'll let you know that the update
was successfully completed and Bastion is ready to boot up. :smile:

Now you can start Bastion, as usual, using the following command:
```bash
./bastion.sh --start
```

## Updating Bastion on Windows

Go to your Bastion directory (it's in your User Directory - `%USERPROFILE%` or
`C:\Users\<User Name>` - if you haven't changed the default installation
directory and path).

**Right-Click** on the `bastion.cmd` script/file and Click **Run as
Administrator** and type `U` or `Update Bastion` and press <kbd>Enter</kbd> to
start the update.

Wait for a few moments for the updater to finish updating.

After the updater has updated Bastion, it'll let you know that the update
was successfully completed and Bastion is ready to boot up. :smile:

Now you can start Bastion, as usual, by **Double-Clicking** the `bastion.cmd`
script/file.
