![status](https://img.shields.io/badge/status-stable-brightgreen)
![language](https://img.shields.io/badge/docker-nginx-php-blue)
![last_commit](https://img.shields.io/github/last-commit/priegue/docker-microservices-nginx-php)
![repo_size](https://img.shields.io/github/repo-size/priegue/docker-microservices-nginx-php)
![license](https://img.shields.io/badge/license-free-lightgrey)

# 🐳 Docker Microsserviços – Nginx + PHP

🌎 **Idiomas**  
🇧🇷 Português (atual)  
🇺🇸 [English](./docs/README-en.md)  
🇪🇸 [Español](./docs/README-es.md)

Projeto prático de **Docker e Microsserviços**, desenvolvido como parte de um desafio educacional da **DIO**, com foco em isolamento de aplicações, independência entre infraestrutura e código e boas práticas iniciais de containers.

------------------------------------------------------------

## 📌 Sobre o projeto
Este projeto demonstra a criação de uma aplicação web simples utilizando **Docker**, **Nginx** e **PHP**, organizada em containers.

O objetivo é aplicar conceitos fundamentais de **microsserviços**, abstraindo o ambiente de execução da aplicação e facilitando portabilidade, versionamento e replicação.

O desafio é baseado no projeto de referência **Toshiro Shibakita**, com adaptações e organização próprias.

------------------------------------------------------------

## 🧱 Arquitetura
- Container Docker
- Servidor web **Nginx**
- Aplicação **PHP**
- Configuração customizada do Nginx
- Estrutura preparada para evolução em microsserviços

------------------------------------------------------------

## 🛠 Tecnologias utilizadas
- Docker
- Nginx
- PHP
- Linux
- Git e GitHub

------------------------------------------------------------

## 📂 Estrutura do projeto
- Dockerfile        → Build da imagem Docker
- nginx.conf        → Configuração do Nginx
- index.php         → Aplicação PHP
- system_data.sql   → Exemplo de estrutura de dados
- docs/             → Documentação multilíngue

------------------------------------------------------------

## ▶️ Como executar

### Pré-requisitos
- Docker instalado  
https://docs.docker.com/get-docker/

### Passos

1) Build da imagem:
```bash
docker build -t nginx-php-app .

2) Executar o container:
docker run -p 8080:80 nginx-php-app

3) Acesse no navegador:
http://localhost:8080

------------------------------------------------------------

## ⚠️ Observações importantes
- Projeto voltado para estudos e laboratório
- Não indicado para produção sem ajustes de segurança
- Ideal para compreender a base de Docker e microsserviços

---

## 📚 Referências
- Repositório base (DIO):  
  https://github.com/denilsonbonatti/toshiro-shibakita

- Docker Docs:  
  https://docs.docker.com/

- Nginx Docs:  
  https://nginx.org/en/docs/

---

## 📄 Licença
Projeto livre para estudo e modificação.

---

## ⭐ Sobre este repositório

Este projeto faz parte do meu portfólio de estudos em Docker, Linux e DevOps, desenvolvido durante minha formação e prática contínua em containers e arquitetura de aplicações.

### ✔ Competências aplicadas
- Containerização com Docker
- Conceitos iniciais de microsserviços
- Servidor web Nginx
- Aplicações PHP em containers
- Organização de projetos para portfólio
- Versionamento com Git
- Documentação técnica

Projeto desenvolvido para fins educacionais e de portfólio.
