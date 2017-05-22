Testing `git out` command...

```
git config --global alias.out '!git checkout -b $USER-out-`date +%s`;
   git add -A; git commit -m "I am out!"; git push -u origin HEAD'
```

```
git out
```
