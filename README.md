# 423-project
to make changes, simply open or create some file in your local version. If you created a file, you have to do:

``git add [new_file_name]`` 

to make `git` track the file. If you edited an already tracked file, you don't have to add it. Then:

``git commit -am [commit_message]``

will commit the change. `commit_message` is something that describes the type of change you made. Good commit messages are descriptive, easy to understand, and correspond well with the actual changes made. Finally:

```
git pull origin master
git push origin master
```

will pull the remote code and then push the commit to the repository on Github. 

**The code that is on the Github server (not the version on your local machine) is the code we will run our tests on. If you don't push a commit, we won't see it and we won't grade it.**

## Running the test cases