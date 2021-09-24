# GIT practice

- hello git!

| table | practice | baby! |
| :---- | :------: | ----: |
| 1     |    2     |     3 |
| 45    |    67    |    87 |

## 上課筆記與心得

Node is a eviroment rather than language.

### git comand

- git config:
  - git config (--global user.name/ user.email)
  - git config --list
    ![image](https://i.imgur.com/iYbhwu4.png)
- repository
  - to build:
    - git init <-> rm -r .git
  - to modify:
    - git status
    - git add
    - git commit -m "(description)"
    - git diff
    - git restore --staged //undo
    - git checkout
    - git checkout HEAD~2 //go back 2
    - git checkout HEAD //come current
    - git log (file)
    - git blame // who the hell did this?
- Branch
  - git branch -m master main
  - git branch
  - git switch
  - git merge
    ###git flow
    ![gitFlowImage](https://i.imgur.com/rV7GdFn.png)

| Windows | MacOS/Linux |             description |
| :------ | :---------: | ----------------------: |
| cd      |     cd      |        change directory |
| cd      |     pwd     |             where am I? |
| cd      |     pwd     |   what do we have here? |
| mkdir   |    mkdir    |          make directory |
| copy    |     cp      |                    copy |
| move    |     mv      |                    move |
| del     |     rm      |                  remove |
| cls     |    clear    |       clear the console |
| cat     |     cat     | what's inside the file? |
