Pull Request Merge Method Comparison
====================================

There were no merge conflicts using this method.

```
$ git log --graph --decorate --format=oneline --abbrev-commit --all
*   f33af42 (HEAD -> master, origin/master, origin/HEAD) Merge pull request #6 from dfrnswrth/branch5
|\
| * 93ab6e5 branch 5
* |   2c42816 Merge pull request #5 from dfrnswrth/revert-4-branch4__pr_will_be_reverted
|\ \
| * | ddb983e Revert "branch 4"
|/ /
* |   0cab7ef Merge pull request #4 from dfrnswrth/branch4__pr_will_be_reverted
|\ \
| * | 14b6f4b branch 4
| |/
* |   abc9758 Merge pull request #3 from dfrnswrth/branch3__from_branch2
|\ \
| * | 82b6c16 branch 3, created from branch 2
* | |   407ca54 Merge pull request #2 from dfrnswrth/branch2
|\ \ \
| |/ /
| * | dc558f2 branch 2
| |/
* |   1988328 Merge pull request #1 from dfrnswrth/branch1
|\ \
| |/
|/|
| * e4c4885 branch 1
|/
* f23cea3 initial commit - create README.md
```

