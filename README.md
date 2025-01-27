[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://opensource.com/resources/what-open-source)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

#

# Food Menus

This project aims to collect the images of food menus of restaurants and hotels. It helps to guide the  beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

Make sure you have some good images of food menu from your favorite restaurants. OR, come back when you have cliked one.

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).


## Fork this repository

Fork this repository by clicking on the fork button on the top right of this page.
This will create a copy of this repository in your account.

<img src="https://raw.githubusercontent.com/foodmenus/foodmenus/main/materials/fork.JPG" width="400">

## Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

<img src="https://raw.githubusercontent.com/foodmenus/foodmenus/main/materials/clone.JPG" width="400">

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

For example:

```
git clone https://github.com/this-is-your-username/foodmenus.git
```

where `this-is-your-username` is your GitHub username. Here you're copying the contents of the foodmenus repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd foodmenus
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-your-username-image
```

## Make necessary changes and commit those changes

Now Copy your image into the menus folder. Make sure you are using a unique name and not replacing the existing file name. Also, please make sure the images are captured with good angle, and the contents are readable. (Preferablly scanned with something like Camscanner or Phone Scanner Apps.)

[Optional] Now open `Contributors.md` file in a text editor, add your name to it. Now, save the file.

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add .
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> 's image"
```

replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin -u <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

<details>
<summary> <strong>If you get any errors while pushing, click here:</strong> </summary>

- ### Authentication Error
     <pre>remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
  remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
  fatal: Authentication failed for 'https://github.com/<your-username>/first-contributions.git/'</pre>
  Go to [GitHub's tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) on generating and configuring an SSH key to your account.

</details>

## Submit your changes for review

Once the changes are pushed, if you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.



Now submit the pull request.



Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor!

Celebrate your contribution and share it with your friends.
