[Go Back](../README.md)
___
# Git Commands

### Delete Branches 

**Filtering by name or partial name of the branch** 

```shell
# delete branch that contains word "chore"
git branch | grep "chore" | xargs git branch -D
```

**Filtering ignoring by branch name** 

```shell
git branch | grep -i -v "main" | xargs git branch -D
```

___
[Go Back](../README.md)