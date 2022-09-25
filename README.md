# # HacktoberFest 2022

This project aims to help the beginners to contribute to the open source and participate in **Hacktoberfest 2k22**.

After completing all the below tasks your details will be published on this website:
[Hacktoberfest](https://niteshjitender.github.io/HacktoberFest2022/)

## What is Hacktoberfest?
A month-long celebration from October 1st - 31st sponsored by [Digital Ocean](https://hacktoberfest.digitalocean.com/) and [GitHub](https://github.com/blog/2433-celebrate-open-source-this-october-with-hacktoberfest) to get people involved in [Open Source](https://github.com/open-source). Create your very first pull request to any public repository on GitHub and contribute to the open source developer community.
##



<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.


## Clone the repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now the next step clonning, Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/HacktoberFest.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Now go to the directory where you have taken the checkout:
```
cd HacktoberFest
```

Now create a branch using the `git switch` command:

```
git switch -c your-new-branch-name
```

For example:

```
git switch -c firstContribution
```

## Make necessary changes and commit those changes

### 1. Add your name (First Contirbution) 

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
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

* ### Authentication Error
     <pre>remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
  remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
  fatal: Authentication failed for 'https://github.com/<your-username>/first-contributions.git/'</pre>  
   Go to [GitHub's tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) on generating and configuring an SSH key to your account.

</details>

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

**Congrats you have succesfully raised your first *PR***

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?
 
 You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor!

### 2. Add your profile pic
Now go to the [MyFirstContribution/userImageData](https://github.com/niteshjitender/HacktoberFest/tree/main/MyFirstContribution/userImageData)
Here you have to add the profile pic that is being shown in the website.
Just add your profilepic with your *Github username*

Now Add, Commit with meaningful message, raise PR.

### 3. Add your data to show the card on the website

Now go to the [MyFirstContribution/script.js](https://github.com/niteshjitender/HacktoberFest/blob/main/MyFirstContribution/script.js)
Add your details to the script.js file
Now Add, Commit with meaningful message, raise PR.


**Congrats,** You have successfully contributed, now you can see your card will appear on the below website after successfully merging of your PR. Celebrate your contribution and share it with your friends and followers by going to [Hacktoberfest](https://niteshjitender.github.io/HacktoberFest2022/) 
Ref: [Firstcontributions](https://github.com/firstcontributions/first-contributions)

 **Keep Contributing!!**
