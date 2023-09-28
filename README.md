Workspace do ROS indigo com todas as informações necessárias pro funcionamento da câmera ASTRA, e como fazer com que o computador NUC deste converse com a base, pra facilitar quem usar o turtlebot com base Kobuki.


### COISAS NECESSÁRIAS PRA RODAR:

-ROS indigo, com todas as dependências.

-Este diretório.

-Talvez uma versão mais recente do CMAKE, mas depois de um bom perrengue descobri que talvez isso não seja necessário.

-Os arquivos dentro deste source.

-Rviz.

-Cabo USB-B, para ligar do NUC à base.

-certas regras UDEV que provavelmente são necessárias caso haja algum erro nas compilações (nada que não seja pesquisável no google).


### LINKS ÚTEIS:

Passo a passo para a inicialização da base e a instalação do ROS: http://learn.turtlebot.com/2015/02/01/6/

Tutorial para a câmera: https://www.dropbox.com/sh/w5w62dnsizrmx2y/AAACCs5vcrVBxsPwD7jtchj7a?dl=0&preview=ROS_orbbec_camera.pdf

Navigation ainda está para ser testado, mas até o momento o primeiro link possui passo a passo para utilizá-lo também.


### COMO INSTALAR ESSE DIRETÓRIO???

É bem simples desde que você já tenha um conhecimento prévio de ROS.

Abra um novo terminal e entre neste diretório.
```
 cd ros_ws
```
após, rode este comando:
```
catkin_make
```

Assim o CMAKE já irá começar a instalação deste diretório no computador.

Em dúvida de erros por dependências que podem vir a ocorrer, recorra aos links disponibilizados acima.



