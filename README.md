# Instalador Whaticket SaaS - Redis em Docker

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

### Atualizar o Fuso Horário conforme o local da sua instalação
dpkg-reconfigure tzdata
```

### Atualize o sistema e instale os pacotes necessários.

```bash
sudo apt -y update && apt -y upgrade
```
Instalação com docker / Ubuntu 22

Adcione manualmente o usuário deploy:

useradd -m -p [[senhadeploy]] -s /bin/bash -G sudo deploy
usermod -aG sudo deploy

cd /home

```bash
sudo apt install -y git && git clone https://github.com/wesleybgm01/autozap6.0install.git autozap6.0install && sudo chmod -R 777 autozap6.0install  && cd autozap6.0install  && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && cd ./install && sudo ./install_instancia
```

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

## Requisitos

| --- | Mínimo | Recomendado |
| --- | --- | --- |
| Node JS | 14.x | 16.x |
| Ubuntu | 18.x | 20.x |
| Memória RAM | 2Gb | 4Gb |  

