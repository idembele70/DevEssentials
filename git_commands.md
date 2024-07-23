**Create a git lg alias**
```bash
git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --"
```
**Change local commit signature**
----
```bash
git config --local user.name <username>
git config --local user.email <email>
```

**Remove a commit**
 ----
 ```bash
git lg 
 ```
![image](https://github.com/user-attachments/assets/233f09f1-c3ee-41a7-b2be-7ce0ed924e1c)

```bash
 git rebase -i <commit-number>
 ```
![image](https://github.com/user-attachments/assets/401da945-540c-4564-ba9d-37a5ec21f956)

- Replace pick with d or drop. Save your changes & close the editor.
```bash
 git push --force-with-lease
 ```
 
 **Discard Local changes in a file**
 ----
 ```bash
 git restore <filename>
 ```
