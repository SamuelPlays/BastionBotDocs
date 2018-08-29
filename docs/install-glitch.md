description: Read how to install and configure Bastion Bot in Glitch. One step closer to making your Discord Server AWESOME!

# Installing Bastion in Glitch

## Initial Setup (GitHub)
Before you can install Bastion in Glitch, the following steps needs to be
performed:

  * Go to [GitHub](https://git-scm.com/downloads).
  * Either [**sign in** or **sign up** for GitHub](https://github.com/login).
  * Go to [Bastion's repository](https://github.com/TheBastionBot/Bastion).
  * Create a [**fork** of Bastion's repository](https://github.com/TheBastionBot/Bastion/fork).
  * Go to the forked repository. It will be in your repositories.
  * Go to **Settings**, and then click on the **Branches** tab in the left.
  * Change the default branch from `master` to `stable`.

## Initial Setup (Glitch)
  * Go to [Glitch](https://glitch.com)
  * And then **Sign in with GitHub**.
  * Now create a **New Project** in Glitch.
  * **Make your project private before doing anything else so that your
    credentials are safe from others. If you're not able to do this, ask around
    in [Bastion HQ](https://discord.gg/fzx8fkt) and some amazing people will
    help you out**.
  * Go to **Project Options** (in the top left corner) and click on **New
    Project** and then click on **clone-from-repo**.
  * Type the following in the prompt, replacing `github_user_name` with your
    GitHub username and `bastion_repo_name` with the name of the repository
    you forked (will be `Bastion` by default):
    ```
    https://github.com/github_user_name/bastion_repo_name.git
    ```
    For example, [my GitHub username is `k3rn31p4nic`](https://github.com/k3rn31p4nic)
    and my forked repository name is `Bastion`, so I'll write:
    ```
    https://github.com/k3rn31p4nic/Bastion.git
    ```
  * Bastion will now be imported to Glitch in a few seconds.


## Setup Bastion in Glitch
  * You'll see a list of Bastion's files in the left side in Glitch.
  * Find the `settings/config_example.json` &
    `settings/credentials_example.json` files. *Don't worry. Files are ordered
    alphabetically.*
  * Make a copy of both the files and rename the copies to `settings/config.json`
    and `settings/credentials.json`, respectively.

## Configure Bastion
  * Edit the `config.json` and `credentials.json` files to make any changes you
    want. *Don't worry about saving, files are automatically saved!*

## Run Bastion
- Bastion will be up and running by now, *automatically*!
