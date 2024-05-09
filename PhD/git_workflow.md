# One file made the workflow simple
 First, we assume that we have three part for the workflow: remote, local, disk.
The flow like this: remote-> local-> disk

1. Clone the git. Now remote is copied in the local and disk.
```
git clone 
```

2. Creat one new branch. First we want to maintain the main branch concise and simple for everyone work for it. Hence we need to create a new branch for our modification. Now we create a new branch:
```
git checkout -b my-feature
```

3. Add the modification in current branch. 
```
git add <>
```

4. local is commited but main is not commited.
```
git commit
``` 

The next step is very important. The situation is that main branch of remote is modificated by others. We need to update others change. Hence, we choose the followeing workflow.
-. change the main branch of local for sycronize the one of remote
-. rebase the main branch of local.
5. Switch into the main branch of local.
```
git checkout main
```
pull the remote 
```
git pull 
```

6. Rebase the main 
Swich into my-feature branch of local.
```
git checkout
```

