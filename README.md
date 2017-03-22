# BK Digital Guides, how to speak laravel.
This demo app is a setup and installing guide for making new
repositories with github. This is also the documentation for the laravel
working way.


# Table of Contents

1. [Create and install new projects](#create-and-install)
	* [Step 1. Create ](#)
	* [Step 2. Clone](#)
	* [Step 3. Create laravel](#)
	* [Step 3. Commit changes](#)
2. [Updating an existing app](#update)


#Installation new (laravel) app <a name="create-and-install"></a>

## Step 1. Create your new app on github.com
On the left side of your profile page, under "Organizations", click the Bureau Kellerman or For Sale account
icon for your organization. Create a new repository.

## Step 2. Clone this app
When your done creating you have to make a clone of this repository. A
simple way is to clone this app trough the Github desktop app. Download
the app here https://desktop.github.com.

Alternatively you can use the command line.

``` 
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

## Step 3. Create Laravel app
Ok. Lets make some code! Open the application in your phpstorm and create a new laravel app
	
```
$ laravel new src
```
	
Doens't work the `$ laravel` command? Alternatively use this: ```$ composer create-project --prefer-dist laravel/laravel src```


### No php storm?
	
``` 
$ cd /*local-path-to-github-project*/ 
$ laravel new src 
```

## Step 4. Make and commit changes
When your done you can commit your changes trough the github desktop app.

Alternatively you can use the command line.

``` 
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```
	

#Updating an existing app	<a name="update"></a>

## Step 1. Clone the app to your machine
A simple way is to clone this app trough the Github desktop app. Download
the app here https://desktop.github.com.

Alternatively you can use the command line.

``` 
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

## Step 2. Make a branch

A simple way is to create your branch trough the Github Desktop App.
Click on the branch icon, in the Name field, type a meaningful name for
your branch and create your branch.
![https://help.github.com/assets/images/help/desktop/create-branch-icon-mac.png](https://help.github.com/assets/images/help/desktop/create-branch-icon-mac.png)

Alternatively you can use the command line.

``` 
$ git branch <BRANCH>
```

__Keep in mind we'r always branching.__ 
Branching is a core concept in Git, and the entire GitHub Flow is based
upon it. There's only one rule: anything in the master branch is always
deployable.
Because of this, it's extremely important that your new branch is
created off of master when working on a feature or a fix. Your branch
name should be descriptive (e.g., `refactor-authentication`,
`user-content-cache-key`, `make-retina-avatars`), so that others can see
what is being worked on.


##  Step 3. Commmit your changes.

When your done you can commit your changes trough the github desktop app.
![https://help.github.com/assets/images/help/desktop/commit-button-mac.png ](https://help.github.com/assets/images/help/desktop/commit-button-mac.png )

#### Alternatively use the command line

Add the files in your new local repository. This stages them for the first commit.

```
$ git add .
```
*Adds the files in the local repository and stages them for commit. To
unstage a file, use `$ git reset HEAD YOUR-FILE`.*

Commit the files that you've staged in your local repository.

```
$ git commit -m "First commit"
```

*Commits the tracked changes and prepares them to be pushed to a remote
repository. To remove this commit and modify the file, use `$ git reset
--soft HEAD~1` and commit and add the file again.*

### Creating a partial commit

If one file contains multiple changes, but you only want some of those changes to be included in a commit, you can create a partial commit.
![https://help.github.com/assets/images/help/desktop/partial-commit-mac.gif](https://help.github.com/assets/images/help/desktop/partial-commit-mac.gif "Partial commit")



# Usage

## Workflow
Clone repositories > Create branches > Commit changes > Share code


## Al lot to learn on https://guides.github.com


## Issues 

#Contributing


# Slack


# Todo

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
- [ ] https://guides.github.com/features/mastering-markdown/




First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


Username @mentions

Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

@somegirlspecial
@markbeets
@thetoob
