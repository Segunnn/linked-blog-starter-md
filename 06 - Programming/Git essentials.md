----

### Start
Set global name and email:
```sh
git config --global user.name "Your Name"
```

```sh
git config --global user.email "your.email@example.com"
```

### Common commands
#### git add
Add some files in your next commit:
```sh
git add [filename]
```
Or, you can add all files in your *pwd* by this:
```sh
git add .
```

#### git commit
Time to commit your changes:
```sh
git commit -m "Your message about what you did here"
```

#### git status
At any point, you can check the status of your repository using `git status`. This command provides information about which files are modified, staged, or committed.
```sh
git status
```

#### git branch
Create and name a new branch:
```sh
git branch [branch_name]
```

#### git checkout
Switch between branches:
```sh
git checkout [branch_name]
```

#### git merge
Just merge:
```sh
git merge [branch_name]
```

#### git push/pull
Upload your local changes to GitHub repo:
```sh
git push origin [branch_name]
```
Or create a pull request to upload it:
```sh
git pull origin [branch_name]
```
