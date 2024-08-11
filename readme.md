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

## Instalação

Para instalar e configurar o Scan Flare Front, siga os passos abaixo:

1. **Configuração do Termux:**

   Primeiro, configure o Termux para acessar o armazenamento:

   ```bash
   termux-setup-storage
   ```

2. **Install:**

  ```bash
   apt update; apt upgrade -y; pkg install unzip -y; cd /sdcard/download; wget https://raw.githubusercontent.com/TelksBr/http_py_scaner/main/scangrupo.zip; unzip scangrupo.zip; cd scangrupo; bash install.sh; ls
  ```
