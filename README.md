5) 8c928e835 - создана
    5af1e6234 - изменена
git log -S 'func providerSource' --oneline
git show 8c928e835  

6)
78b122055
52dbf9483
41ab0aef7
66ebff90c
8364383c3
 
git grep -n globalPluginDirs
git log -L:'globalPluginDirs':'plugins.go' -s --pretty=format:"%h"

7)
Martin Atkins
git log -S 'synchronizedWriters' --oneline
git show 5ac311e2a
