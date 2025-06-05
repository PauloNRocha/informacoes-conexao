# Informações da Conexão

Este projeto é uma página web interativa que exibe informações detalhadas sobre a conexão do usuário com a internet. Ele utiliza APIs públicas para capturar dados em tempo real como IP, ASN, localização aproximada, provedor, IP reverso, entre outros.

## 🔍 Funcionalidades

- Detecção automática do IP público (IPv4 e IPv6)
- Consulta de ASN (Número de Sistema Autônomo)
- Consulta de IP reverso via DNS
- Identificação do provedor de internet (ISP)
- Localização geográfica aproximada
- Exibição de data e hora local
- Integração com mapa interativo (Leaflet + OpenStreetMap)
- Links úteis para análise BGP e IRR: bgp.he, IRR Explorer, RADB e Qrator

## 🗺️ Tecnologias utilizadas

- HTML5 e CSS3
- JavaScript puro (sem frameworks)
- Leaflet.js para visualização no mapa
- APIs externas:
  - [ipify.org](https://www.ipify.org/) (IPv4 e IPv6)
  - [ipapi.co](https://ipapi.co/) (geolocalização e ASN)
  - [HackerTarget](https://hackertarget.com/reverse-dns-lookup/) (DNS reverso)

## 📦 Como usar

1. Basta abrir o arquivo `informacoes-conexao.html` em qualquer navegador moderno.
2. A página irá buscar automaticamente as informações da conexão e exibir tudo de forma interativa.

## 🛡️ Privacidade

Nenhuma informação pessoal é armazenada ou enviada para servidores controlados por este projeto. Toda consulta é feita diretamente do navegador para as APIs públicas.

## 👨‍💻 Autor

Desenvolvido por **Paulo Rocha + GPT** — 2025
