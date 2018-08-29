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
  * Then create a **New Project** in Glitch. It can be of any type.
  * **Make your project private before doing anything else so that your
    credentials are safe from others. If you're not able to do this, ask around
    in [Bastion HQ](https://discord.gg/fzx8fkt) and some amazing people will
    help you out**.
  * Click on the **Logs** button (at the top left corner) in your Glitch project.
    It will open the log window at the bottom, where you can find the **Console**
    button. Click on that and you'll be redirected to your project's console.
  * Now, before we install Bastion, we'll need to clear all files from the default
    project that was automatically created by Glitch. Run the following command in
    your project's console to clean everything up:
```bash
rm -rf /app/* /app/.* 1>/dev/null
```

## Install Bastion
  * First of all, we need to clone (copy) Bastion from your forked repository. Run
    the following command to do that, replacing `github_user_name` with your GitHub
    username and `bastion_repo_name` with the name of the repository you forked
    (will be `Bastion` by default)
```bash
git clone https://github.com/github_user_name/bastion_repo_name.git .
```
   * For example, [my GitHub username is `k3rn31p4nic`](https://github.com/k3rn31p4nic)
    and my forked repository name is `Bastion`, so I'll write:
```bash
git clone https://github.com/k3rn31p4nic/Bastion.git .
```
  * Bastion will now be imported to Glitch in a few seconds.
  * But, when you go to your project editor, you won't see it. *Why?* Because Glitch
    console doesn't sync with your project editor automatically. To do that, run the
    following command:
```bash
refresh
```
  * Now when can go back to your project editor, you'll see that it has been updated.

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

!!! tip "Show your love!"
    If you like Bastion, please consider giving it a :star: on [GitHub](https://github.com/TheBastionBot/Bastion).
