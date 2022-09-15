# Git Commands

### Delete Branches 

**Filtring by name or partial name of the branch** 

```shell
# delete branch that contains word "chore"
git branch | grep "chore" | xargs git branch -D
```

**Filtring ignoring by branch name** 

```shell
git branch | grep -i -v "main" | xargs git branch -D
```