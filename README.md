# votauai
Vota Uai é um sistema simples e funcional de votação, desenvolvido em Drupal 10 com foco em backend e boas práticas de desenvolvimento. O objetivo é permitir que administradores cadastrem perguntas e opções de resposta, enquanto os usuários podem votar e visualizar os resultados, conforme configuração.

Este projeto foi pensado para demonstrar a capacidade de personalização do Drupal, utilizando entidades customizadas, serviços, API REST e uma arquitetura limpa e escalável sem depender de nodes ou módulos contrib.

Funcionalidades:
---

Tecnologia usada: 
Drupal 10
PHP 8.1
Composer
Lando
MySQL
Restful API
Drupal Rest UI

Como rodar o projeto: 
# Clone o projeto
git clone git@github.com:anax4/votauai.git
cd votauai

# Inicie o ambiente Lando
lando start

# Acesse o site
http://votauai.lndo.site

# Instale o Drupal (se necessário)
lando drush site:install
