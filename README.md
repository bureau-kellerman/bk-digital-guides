# glowing-spoon
Demo App and Installing guide


# Create & install new projects

## 1. Create new app on github.com on the BK account

## 2. Clone this app in Github desktop
Keep in mind we'r always branching.  
Branching is a core concept in Git, and the entire GitHub Flow is based
upon it. There's only one rule: anything in the master branch is always
deployable.

Because of this, it's extremely important that your new branch is
created off of master when working on a feature or a fix. Your branch
name should be descriptive (e.g., `refactor-authentication`,
`user-content-cache-key`, `make-retina-avatars`), so that others can see
what is being worked on.



## 3. Open app in php storm and create new laravel app
	
```
$ laravel new src
```
	
Alternatively:
	
```
$ composer create-project --prefer-dist laravel/laravel src
```

### No php storm?
	
``` 
$ cd /\*local-github-project\*/ 
$ laravel new src 
```
	
Alternatively: 

``` 
$ composer create-project --prefer-dist laravel/laravel src
``` 
	

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
