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
- Mudar o install de gcc-9 para gcc-8 (Apenas no Debian)
## Metasploits
- [Configurar Metasploits](https://nullsec.us/integrating-beef-and-metasploit/)
```
sudo service postgreesql start
msfconsole
load msgrpc ServerHost=127.0.0.1 User=msf Pass=<password> SSL=y
```

## VM
 - [Mudar Resolução da VM no Debian](https://www.youtube.com/watch?v=KJ5pObje1Dk)<br>
 ![img](https://github.com/JorgeJabczenski/ic-seguranca/blob/main/imgs/inserir%20imagem%20de%20CD.png)

## Links
- https://blackarch.org/tools.html
- https://www.g2.com/products/beef/competitors/alternatives
- https://linuxsecurity.expert/tools/beef/alternatives/
- https://br.malwarebytes.com/cryptojacking/
- https://github.com/monero-ecosystem/monero-GUI-guide/blob/master/monero-GUI-guide.md
- https://www.getmonero.org/resources/user-guides/
- https://github.com/monero-ecosystem/monero-javascript
- https://www.getmonero.org/resources/developer-guides/

