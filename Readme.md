### New readme

```
git remote add <remote_name> <url>
```
example:

```
git remote add origin https://github.com/Cenfracee/RemoteTest.git
````
Typing `git remote` should now show `origin`


#### pushing

To push the master in the remote repo to cloud repo

example:
```
git push origin master
```



### notes
https://choosealicense.com/


What is a tracking branch

It is a local branch tracking a remote branch

To list all remotes
```
git remote -v
```

List tracking branches
```
git branch -vv
```

```
git push -u origin master
```

###credentail store

add credential helper

```
git config --global --list
git config --global --add credential.helper store
````
First use of credential will save it to credential.helper



flex-direction
flex-wrap
flex-flow
https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox_skills
https://flexboxfroggy.com/
https://www.learnflexbox.org/
justify-content
align-items
align-self
