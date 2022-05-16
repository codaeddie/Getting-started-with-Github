# Intro to GitHub + Ubuntu
Github allows us to share out git repositories with friends, peers, and everyone else.
I won't get into the the difference between the main technology of Git, and the site Github.

## Table of contents
* [Using Ubuntu](https://github.com/codaeddie/Getting-started-with-Github/blob/main/README.md#using-ubuntu)
* [Links for Help](https://github.com/codaeddie/Getting-started-with-Github/blob/main/README.md#links-for-help)
* * [Setup](#setup)
* * [Setup](#setup)


## Let's start by imagining you're working on a project.
I've found that the best way to learn is to experience the challenges first hand and go at your own pace in trying to solve it. That being said, let's imagine youre working on a project and a couple of friend's are intrested in joining you and helping you build this project.

There are a couple different way's you could go about starting. For the sake of this tutorial lets say all you have is a text file named "game_plan.txt"
In this text file, you listed the project plan, functionality, and requirements for you to begin the project. 

#### You want to share this text file with the friend's that want to help:

After creating a github account, you'll start by selecting the " + " sign drop-down menu and clicking "New Repository"
 - This will take you to creation page for your new repository.
 - on the creation page, you can name your repository,
 - label a description for it, 
 - select whether you want it public or private, 
 - and chose to initialize it with a "README"

Once you've selected the desired preferences, click the green "Create repository" button on the bottom.

#### After you click the Create repository button, you will be redirected to the Quick setup-page

Here you can see a number of different options, 

## Using Ubuntu
### Lets run through some commands and intro to github through command line 

_Remember_ if you are having any troubles, a good starting point will always be using the ```--help``` command after your argument

Getting started with this project:
```
git branch
git push
git branch --help
git status
git branch
git checkout
git commit -m 'Updating & debuggging ThisClass'
git push origin HEAD:ThisClass
git pull --rebase
git add
git commit
```

- [x] Create Repo 
- [x] Push Code from Local Machine into Repo
- [ ] Add delight to the experience when all tasks are complete :tada:


![alt text](https://github.com/codaeddie/Getting-started-with-Github/blob/9873b1b0c2fcc367419f8c501a19a2ddec5d5c7f/images/wu.png "Protect Ya Neck")

## Links for Help

#### If you want to learn about Github Keyboard short-cuts, follow this link:
- https://docs.github.com/en/get-started/using-github/keyboard-shortcuts
#### If you want to learn about Github basic formatting, follow this link:
- https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax


```
Inline-style: 
![alt text](https://github.com/codaeddie/codaeddie.github.io/blob/701968afbffca8ceedd13bdd1a6987e81734c011/images/wu.png "Protect Ya Neck")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/codaeddie/codaeddie.github.io/blob/701968afbffca8ceedd13bdd1a6987e81734c011/images/wu.png  "Protect Ya Neck"
```
## Code Blocks 
We can segment code blocks and provide language-specific code matches

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

