---
layout: default
title: Guildas
---

# Guildas

---

## Associações

As guildas são organizadas em associações para facilitar a cooperação entre profissões similares.  

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
* Guilda dos Correeiros

</div>

## Associação de Metais & Pedras

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
* Guilda dos Candeeiros
* Guilda dos Construtores Navais

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
* Guilda dos Herbalistas
* Guilda dos Alquimistas
* Guilda dos Perfumistas
* Guilda dos Peixeiros

</div>

## Associação das Armas

<div class="column-list" markdown="1">

* Guilda dos Mercenários
* Guilda dos Arqueiros
* Guilda dos Caçadores
* Guilda dos Domadores
* Guilda dos Escudeiros
* Guilda dos Cavaleiros
* Guilda dos Patrulheiros
* Guilda dos Gladiadores
* Guilda dos Duelistas
* Guilda dos Caçadores de Recompensa

</div>

## Guildas Independentes

<div class="column-list" markdown="1">

* Guilda dos Jirinadores
* Guilda dos Mercadores
* Guilda dos Magos Independentes
* Guilda dos Banqueiros
* Guilda dos Estalajadeiros
* Guilda das Meretrizes
* Guilda dos Ladrões

</div>

## Lista de Guildas

{% for g in site.data.guilds.guilds %}
---

### {{ g.name }}
<aside>Localização: Distrito X<br/>Categoria: {{ g.categoria }}</aside>
{{ g.description }}
<br/><br/>
{% endfor %}
