# IC Segurança
<b> Consulta rápida para as coisas que eu preciso na ic </b>

## Debian
- Para dar root para o usuário, editar o arquivo /etc/sudoers e adicionar
```
user ALL=(ALL:ALL) ALL
```

- Mudar o espelho no /etc/apt/sources.list
```
# deb cdrom:
deb http://deb.debian.org/debian buster main contrib
deb-scr http://deb.debian.org/debian buster main contrib
deb http://deb.debian.org/debian buster-updates main contrib
deb-scr http://deb.debian.org/debian buster-updates main contrib 
deb http://security.debian.org/debian-security buster/updates main contrib
deb-src http://security.debian.org/debian-security buster/updates main contrib
```
- Instalar as coisas necessárias
```
sudo apt install ltrace strace git vim
```
## Beef
- [BeEF](https://beefproject.com/)
- Mudar o install de gcc-9 para gcc-8

## VM
 - [Mudar Resolução da VM no Debian](https://www.youtube.com/watch?v=KJ5pObje1Dk)<br>
 ![img](https://github.com/JorgeJabczenski/ic-seguranca/blob/main/imgs/inserir%20imagem%20de%20CD.png)

