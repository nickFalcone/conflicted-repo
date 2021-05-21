# conflicted-repo

Used to test git merge conflicts for the [Git Conflict Bot](https://github.com/nickFalcone/git-conflict-bot).

To generate conflicts: 

```bash
git clone git@github.com:nickFalcone/conflicted-repo.git
cd conflicted-repo/
git checkout master
git pull origin conflicts

# CONFLICT (content): Merge conflict in lorem.txt
# Automatic merge failed; fix conflicts and then commit the r
```