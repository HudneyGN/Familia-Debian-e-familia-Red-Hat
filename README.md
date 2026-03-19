# 🧪 Enterprise Lab - Linux + Windows + Active Directory

Simulação de ambiente corporativo com integração entre **Windows Server (Active Directory)** e servidores **Linux (Debian e CentOS)**.

---

## 📸 Visão Geral

![Lab Diagram](./images/lab-diagram.png)

![Hyper-V Lab](./images/hyperv-lab.png)

---

## 🎯 Objetivo

Construir um ambiente realista de infraestrutura de TI para prática de:

* Administração de servidores Windows (AD DS)
* Administração Linux (Debian e CentOS)
* Configuração de rede corporativa
* Integração entre sistemas heterogêneos
* Acesso remoto e serviços

---

## 🏗️ Arquitetura

* Domínio: `lab.local`
* Rede: `172.23.192.0/24`
* DNS centralizado no Domain Controller

---

## 🖥️ Infraestrutura

| Host   | Sistema        | Função                    | IP            |
| ------ | -------------- | ------------------------- | ------------- |
| DC01   | Windows Server | Domain Controller (AD DS) | 172.23.192.10 |
| WIN10  | Windows 10     | Cliente do domínio        | 172.23.192.20 |
| DEBIAN | Debian         | Servidor Linux (SSH)      | 172.23.192.11 |
| CENTOS | CentOS Stream  | Servidor Linux (SSH)      | 172.23.192.12 |

---

## 🪟 Active Directory

* Instalação da role AD DS
* Criação do domínio `lab.local`
* Gerenciamento de usuários
* Autenticação centralizada

---

## 🐧 Linux Servers

### Debian e CentOS

* Configuração de IP estático
* Definição de DNS apontando para o AD
* Instalação e configuração do SSH
* Comunicação com ambiente Windows

---

## 🔐 Acesso Remoto

* SSH habilitado nos servidores Linux
* Testes de conexão entre máquinas
* Base para administração remota

---

## 🌐 Configuração de Rede

* IP estático manual
* Gateway e DNS configurados
* Comunicação validada via ping

---

## 🧪 Testes realizados

* ✔️ Ping entre todas as máquinas
* ✔️ Cliente Windows autenticando no domínio
* ✔️ Acesso SSH funcional
* ✔️ Resolução DNS pelo AD

---

## 🧠 Skills Demonstradas

* Active Directory (AD DS)
* Linux Administration
* Network Configuration
* DNS e resolução de nomes
* Integração Windows + Linux
* Troubleshooting básico

---

## 🚀 Próximas Implementações

* [ ] Integração Linux no domínio (realmd / winbind)
* [ ] Servidor Samba com AD
* [ ] Controle de permissões por usuário
* [ ] Nginx/Apache em ambiente corporativo
* [ ] Monitoramento e logs

---

## 👨‍💻 Autor

**Hudney Gomes Nunes**

💼 Analista de TI em formação
🚀 Foco em Infraestrutura, Linux e Redes

---

## ⭐ Sobre o Projeto

Este laboratório foi desenvolvido com foco em aprendizado prático, simulando cenários reais encontrados em ambientes corporativos.
