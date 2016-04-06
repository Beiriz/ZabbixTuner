# ZabbixTuner

ZabbixTuner é um projeto que utiliza a API do Zabbix que tem como objetivo verificar uma instalação do Zabbix e propor ajustes para melhorar a performance e a estabilidade do sistema.

## Instalação

```sh
$ sudo apt-get install pip git

$ git clone https://github.com/janssenlima/ZabbixTuner
$ cd ZabbixTuner
$ sudo pip install -r requirements.txt
```

## Configurar parâmetros de conexão do Zabbix

>Inserir URL, usuário e senha de acesso ao Zabbix

```sh
$ vim conf/zabbix.py
```

## Execução

```sh
$ ./ZabbixTuner.py
```
