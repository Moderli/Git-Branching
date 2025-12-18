# Git-Branching
A documentation of git branching practice problems from "Learn Git Branching"
## Section 1 Level 1
First level was about commits, it is used to commit the code, the advantage is that the previous code and the new code will be saved. and the new commit will be saved as new main*
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/38da8e2c-f279-45d9-a1c8-2fb2b24321e2" />

## Section 1 Level 2
This Level shows the usage of branches, and swiching between branches 
```$ git branch bugFix```
this command is used to create a new branch.
<img width="222" height="244" alt="image" src="https://github.com/user-attachments/assets/6cc6c3c3-01bc-4076-9858-ef3968e50407" />
if we want to checkout that new branch we can use the below commad
```$ git checkout bugFix```
<img width="226" height="350" alt="image" src="https://github.com/user-attachments/assets/f6da33c5-4393-4dea-b306-3879cdcaf73d" />

## Section 1 Level 3 
This section talkes about merge, Merging in Git creates a special commit that has two unique parents.
```
$ git branch bugFix
$ git chechout bugFix
$ git commit
```
<img width="231" height="331" alt="image" src="https://github.com/user-attachments/assets/38964380-e5cc-48b1-a4c1-9b888864260b" />

```
$ git checkout main
$ git commit
```
<img width="570" height="353" alt="image" src="https://github.com/user-attachments/assets/4ae1e182-b0a9-4d47-b219-c37c11466414" />

now we need to merge useing the below command

```
$ git merge bugFix
```
<img width="872" height="485" alt="image" src="https://github.com/user-attachments/assets/2e1376f2-b30b-414c-9821-4c24434599c4" />

## Section 3 Level 3

if we want some work x needs to be set under the main* then we need to use rebase command
```$ git rebase ```

so as per the problem

```
$ git branch bugFix
$ git checkout bugFix
$ git commit
$ git checkout main
```
<img width="214" height="334" alt="image" src="https://github.com/user-attachments/assets/a0eb7252-ca22-4da4-9ddb-fa26a0db44a7" />
```
$ git commit
$ git checkout bugFix
```
```
$ git rebase main
```
<img width="633" height="422" alt="image" src="https://github.com/user-attachments/assets/a0223470-cd6e-4b04-b9f3-d04c48572ad2" />

