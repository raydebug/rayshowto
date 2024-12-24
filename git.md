
# delete local and remote branches which are already merged
git branch --merged main | grep -v '\*\|main' | xargs -n 1 git push origin --delete && git branch --merged main | grep -v '\*\|main' | xargs -n 1 git branch -d
