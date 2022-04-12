# Azure IoT Edge Device | Local IoT Gateway 

Dentro desta pasta há um conjunto de projetos que oferecem formas diferentes de se preparar um ambiente virtualizado que funciona como um dispositivo IoT de borda (Edge) local, ou seja, uma Gateway virtualizada. 


## Índice
+ **1_Maquina_Virtual_Edge_Azure**
    + Projeto que cria um dispositivo IoT Edge com o ecosistema Azure "IoT Edge Runtime" configurado e pronto a correr. Neste projeto, a máquina virtual corre dentro da nuvem Azure, portanto é uma opção válida apenas para se colocar um dispositivo IoT Edge a correr logo desde o arranque. Esta máquina também é útil de ser usada no caso de se querer desenvolver módulos aplicacionais a correr dentro do dispositivo IoT Edge, aonde se usa esta máquina para testar a sua devida execução, ou seja ambiente de debug/test.
+ **2_Maquina_Virtual_Local_Gateway**
    + Projeto que disponibiliza uma máquina virtual Linux Ubuntu, a ser executada localmente num computador, para que este assuma a função de dispositivo IoT Edge (Gateway de/para a nuvem). Esta máquina foi preparada para ser executada em Windows, e deve de ser portável para ser executada noutros ambientes onde o software **VMWare Workstation Player** corra.
