<img src="https://www.raspberrypi.org/app/uploads/2011/10/buckyball_logo_detailscropped-500x490.jpg" width="80"> <img src="https://web.craftbeerpi.com/assets/images/logo_dark.png" width="250">

# CraftBeerPi V3.0 [PT-BR] + Macetes de Pós Instalação

Esta é a versão 3.0 do CraftBeerPi. Atualmente está em status beta.

## Instale o Raspbian
Através do link abaixo você terá acesso ao software de Instalação do Raspbian

https://www.raspberrypi.org/downloads/

## Vídeo de introdução

https://www.youtube.com/watch?v=YGARUJgFWh4&t=1s

## Instalação

Abra uma janela de terminal no Raspberry Pi e digite:

<code> git clone https://github.com/Manuel83/craftbeerpi3</code>

Isso irá baixar (clonar) o software para o seu Raspberry Pi local.

Digite <code> cd craftbeerpi3 </code> para navegar até a pasta craftbeerpi.

Digite <code> sudo ./install.sh </code>

## Hardware Wiring

Aqui você encontrará um guia como conectar tudo.

http://web.craftbeerpi.com/hardware/

## ATENÇÃO

CraftBeerPi 3.0 é uma reescrita completa. Servidor e interface de usuário. Eu recomendo usar um segundo cartão SD para teste.

## Desenvolvimento baseado em Docker

Para desenvolver este aplicativo ou seus plug-ins em um PC / Mac, você pode usar o arquivo docker-compose:

``` shell
$ docker-compose up
...
Starting craftbeerpi3_app_1 ... done
Attaching to craftbeerpi3_app_1
app_1  | [2018-08-13 12:54:44,264] ERROR in __init__: BUZZER not working
app_1  | (1) wsgi starting up on http://0.0.0.0:5000
```

O conteúdo desta pasta será montado em `/usr/src/craftbeerpi3` e o servidor estará acessível em `localhost:5000`.

## Doação

CraftBeerPi é um projeto de código aberto e gratuito. Se você gosta de apoiar o projeto, Manuel83 vai ficar feliz com a doação:

[![Donate](https://www.paypal.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=2X9KR98KJ8YZQ)

## Macetes de Pós Instalação (Rode os Seguintes Comandos)

<code>sudo apt-get update</code>
<code>sudo apt-get upgrade</code>
<code>sudo apt-get install git</code>
<code>git clone https://github.com/Manuel83/craftbeerpi3</code>
<code>cd craftbeerpi3</code>
<code>sudo ./install.sh</code>
<code>sudo apt-get install python-pip</code>
<code>sudo ./run.py</code>
<code>sudo apt-get install python-pip -y </code>
<code>sudo pip install flask</code>
<code>sudo pip install flask_socketio</code>
<code>sudo pip install flask_classy</code>
<code>sudo pip install PyYAML</code>
<code>sudo pip install GitPython</code>
<code>sudo pip install requests</code>
<code>sudo pip install gitdb2==2.0.5</code>
