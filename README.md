Установить все пакеты используя TeX Live :
```sh
$ cat lecture1.dep | grep -oP '(?<=package}{)\w*' | xargs tlmgr install 
```
Также список всех пакетов приведен в req.txt


