sudoscp
=======

* Use "fabric" to copy files as as sudo user. Source and destination arguments
look like scp: 

```sudoscp filename user@hostname:path```

* The "user" will be the sudo user. It's assumed that your ssh config will take
care of any special login users.

* If you use bash completion, I recommend the following for your .bashrc:

```complete -F _scp -o nospace sudoscp```
