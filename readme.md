# Scan Flare Front

**Autor:** @DarkJVPN

## Visão Geral

Scan Flare Front é uma ferramenta em Python desenvolvida para escanear uma lista de servidores proxy em busca de métodos HTTP suportados. A ferramenta testa cada proxy para vários métodos HTTP, como GET, POST, HEAD, PATCH, PUT, DELETE e OPTIONS, e organiza os resultados em um arquivo chamado `hosts_ordenados.txt`.

## Funcionalidades

- Escaneia servidores proxy em busca de métodos HTTP suportados.
- Exibe um relatório detalhado de sucesso e falha para cada método por proxy.
- Organiza os resultados em um arquivo estruturado para fácil referência.
- Utiliza threads para acelerar o processo de escaneamento.

## Requisitos

- Python 3.x
- Bibliotecas Python necessárias:
  - `http.client`
  - `threading`
  - `time`
  - `pyfiglet`
  - `rich`
  - `collections`

## Uso

1. Prepare um arquivo chamado `allhosts.txt` contendo a lista de servidores proxy que você deseja escanear. Cada proxy deve estar em uma nova linha no formato `hostname:port`.

2. Execute o script:

   ```bash
   python scan_flare_front.py
