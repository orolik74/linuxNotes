Условия зачета: лабы, тест, устное общение
<br>
<br>
___
```bash
htop
``` 

pipe - | соединяет input и output  

```bash
pstree
```
– дерево процессов  
manual: 
```bash
man
```

type - понять, что за команда (useless)
which
print wotking directory:
```bash
pwd
```

export PATH=SPATH: \`pwd\`  
\` – исполнитель и подставить  
```bash
history
```
ctrl + R – для поиска в истории команд
<br>
<br>
___
#### Изменение доступа:
```bash
chmod
```

touch test-file
ls -la – права файла  
d - directory  
l - link  
b - блоковый  
c - поточный

ln -s test-file fff –  
по тройкам разбито на r, w, x
3 тройки: я, группа, все  
r - read
w - write  
x - executable
<br>
<br>
chmod a+x - a - all, x - executable  
dd – побитовое копирование
___
хз, что, но что-то такое делали:
лучше не запускать, я хз, что это))
```bash
mount
dd if=/dev/zero of=secret-data bs=300M count=1 //count обязатлеьно!!!! иначе будет до конца места //лучше в эмуляторе
hexdump
mkfs.ext4 //antipod - wipefs
sudo mount -o loop
```
базовые названия папок линукса и что они значат типа  
home, lib и тд  
etc -- остальное
