<br/>

### HARD
```git
git reset ---hard 2fad
немесе 
git reset --hard @~
```
бір коммитке арқа қайтады

ORIG_HEAD деген бөлініп кеткен, қол жетпейтін коммит,
оны біз git reflog деп қай коммит екенін көріп өте аламыз, 
қол жетпейтін коммиттер 30 күндей сақталады
```git
git reset --hard ORIG_HEAD
```
```git
git reset --hard HEAD // қазіргі state-қа қарайды
```

<br/>
<br/>

### SOFT
```git
git reset --soft @~
```
файлдарды өзгертпейді, олар қала береді
