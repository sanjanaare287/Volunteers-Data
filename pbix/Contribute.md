# How to Submit your report?

If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quote marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

For example:
```
git clone https://github.com/this-is-you/Volunteers-Data.git
```
where `this-is-you` is your GitHub username. Here you're copying the contents of the Volunteers-Data repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd Volunteers-Data
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-new-branch-name-with-your-name>
```

For example:
```
git checkout -b myDataBranch-rose-bush
```
(The purpose of this branch is to recognize your contribution.)

## Add your Power BI File and commit the change

Copy your Power BI Report in the pbix folder.


If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add pbix/your-report-name.pbix
```

Now commit those changes using the `git commit` command:
```
git commit -m "<your-name> submitting the report"
```
replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-new-branch-name-with-your-name>
```
replacing `<add-your-new-branch-name-with-your-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.

Now submit the pull request.

You could join our slack team in case you need any help or have any questions. [Join slack team](https://join.slack.com/t/unitednations-ua03475/shared_invite/zt-ds1htfkw-Abri6NuVKA6P4c~AYvTZhw).