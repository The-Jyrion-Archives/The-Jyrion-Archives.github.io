---
layout: default
title: Guildas
---

# Guildas

---

# Associações

## Associação dos Artesãos

<div class="column-list" markdown="1">

* Guilda dos Marceneiros
* Guilda dos Carpinteiros
* Guilda dos Escribas
* Guilda dos Escultores
* Guilda dos Encadernadores
* Guilda dos Músicos
* Guilda dos Pintores
* Guilda dos Cartógrafos
* Guilda dos Bordadores
* Guilda dos Cesteiros
* Guilda dos Agulheiros
* Guilda dos Fabricantes de Bolsas

</div>

## Associação dos Fabricantes

<div class="column-list" markdown="1">

* Guilda dos Alfaiates
* Guilda dos Coureiros
* Guilda dos Tecelões
* Guilda dos Tanoeiros
* Guilda dos Tingidores
* Guilda dos Sapateiros
* Guilda dos Esfoladores
* Guilda dos Cordoeiros

</div>

## Associação de Metais e Pedras 

<div class="column-list" markdown="1">

* Guilda dos Ferreiros
* Guilda dos Joalheiros
* Guilda dos Pedreiros
* Guilda dos Vidreiros
* Guilda dos Mineiros
* Guilda dos Relojoeiros
* Guilda dos Ourives
* Guilda dos Encanadores
* Guilda dos Velamistas
* Guilda dos Armeiros
* Guilda dos Flecheiros
* Guilda dos Ferreiros de Cavalo
* Guilda dos Carroceiros
* Guilda dos Fabricantes de Telhas

</div>

## Associação dos Produtores

<div class="column-list" markdown="1">

* Guilda dos Padeiros
* Guilda dos Açougueiros
* Guilda dos Ceverjeiros
* Guilda dos Boticários
* Guilda dos Agricultores
* Guilda dos Pescadores
* Guilda dos Vinicultores
* Guilda dos Estalajadeiros
* Guilda dos Herbalistas
* Guilda dos Alquimistas
* Guilda dos Perfumistas
* Guilda dos Peixeiros

</div>

## Guildas Sem Associação

<div class="column-list" markdown="1">

* Guilda dos Construtores Navais
* Guilda dos Ladrões
* Guilda dos Cartógrafos
* Guilda dos Mercadores
* Guilda dos Cirurgiões-Barbeiros
* Guilda dos Arqueiros
* Guilda dos Correeiros
* Guilda dos Banqueiros
* Guilda dos Jirinadores
* Guilda dos Mercenários
* Guilda dos Magos Independentes

</div>

{% for g in site.data.guilds.guilds %}
---



## {{ g.name }}
<aside>Localização: Distrito X</aside>
{{ g.description }}
{% endfor %}
