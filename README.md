Установить все использованные пакеты используя TeX Live :
```sh
$ cat lecture1.dep | grep -oP '(?<=package}{)\k*' | xargs tlmgr install 
```
Также список всех пакетов приведен в req.txt

