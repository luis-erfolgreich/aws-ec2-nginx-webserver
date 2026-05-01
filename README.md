# AWS EC2 NGINX Web Server

Projeto de hospedagem web utilizando Amazon EC2 e NGINX.

## Sobre o projeto

Neste projeto foi criada uma instância EC2 utilizando Amazon Linux 2023 para hospedar uma página HTML com NGINX.

O objetivo foi praticar:

* Criação de instâncias EC2
* Configuração de Security Groups
* Acesso remoto
* Instalação de serviços Linux
* Hospedagem web básica

---

## Tecnologias utilizadas

* AWS EC2
* Amazon Linux 2023
* NGINX
* Linux
* HTML
  

## Configuração do servidor

### Atualização do sistema

```bash
sudo dnf update -y
```

### Instalação do NGINX

```bash
sudo dnf install nginx -y
```

### Inicialização do serviço

```bash
sudo systemctl start nginx
sudo systemctl enable nginx
```


## Resultado

Servidor web rodando publicamente na AWS utilizando NGINX.

---

## Evidências


