1.
Ответ:
    commit aefead2207ef7e2aa5dc81a34aedf0cad4c32545
Комманда: 
    git show aefea
2.
Ответ:
    tag: v0.12.23
Комманда:
    git show 85024d3
3.
Ответ: 
    2 родителя: 
        cd7859e05c36c06b56d013b55a252d0bb7e158, 9ea88f22fc6269854151c571162c5bcf958bee2b
Комманды:  
    git show b8d720
    git show 56cd7859e
    git show 9ea88f22f
4.
Ответ:
    b14b74c4939dcab573326f4e3ee2a62e23e12f89 [Website] vmc provider links
    3f235065b9347a758efadc92295b540ee0a5e26e Update CHANGELOG.md
    6ae64e247b332925b872447e9ce869657281c2bf registry: Fix panic when server is unreachable
    5c619ca1baf2e21a155fcdb4c264cc9e24a2a353 website: Remove links to the getting started guide's old location
    06275647e2b53d97d4f0a19a0fec11f6d69820b5 Update CHANGELOG.md
    d5f9411f5108260320064349b757f55c09bc4b80 command: Fix bug when using terraform login on Windows
    4b6d06cc5dcb78af637bbb19c198faff37a066ed Update CHANGELOG.md
    dd01a35078f040ca984cdd349f18d0b67e486c35 Update CHANGELOG.md
    225466bc3e5f35baa5d07197bbc079345b77525e Cleanup after v0.12.23 release
Комманда: 
    git log v0.12.23..v0.12.24 --pretty=oneline
5. 
Ответ:
    8c928e835 - создана
    5af1e6234 - изменена
Комманды:
    git log -S 'func providerSource' --oneline
    git show 8c928e835
    git show 5af1e6234  
6.
Ответ:
    78b122055
    52dbf9483
    41ab0aef7
    66ebff90c
    8364383c3
Комманды: 
    git grep -n globalPluginDirs
    git log -L:'globalPluginDirs':'plugins.go' -s --pretty=format:"%h"
7.
Ответ: 
    Martin Atkins
Комманды: 
    git log -S 'synchronizedWriters' --oneline
    git show 5ac311e2a
