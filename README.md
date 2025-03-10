# Bitcoin Bloques

## Descripción

Este proyecto consiste en una base de datos extraída mediante scraping de la página [Blockchair](https://blockchair.com/es/bitcoin/blocks/0), la cual proporciona información detallada sobre los bloques de la blockchain de Bitcoin.
Respecto al uso, el archivo unificado de los datos se encuentra en la carpeta [Archivos Comprimidos]([https://blockchair.com/es/bitcoin/blocks/88708](https://github.com/amiguelalvarez/bitcoinbloq/tree/main/blockchair_bitcoin_blocks_dta)), descarguen y descompriman los archivos para su uso.

## Fuente de los Datos

- **Origen:** [Blockchair](https://blockchair.com/es/bitcoin/blocks/0)
- **Fecha del Scraping:** 9 de marzo de 2025
- **Tipo de Datos:** Información sobre bloques de la blockchain de Bitcoin

## Contenido de la Base de Datos

Los datos recopilados incluyen:

- Altura del bloque
- Hash del bloque
- Cantidad de transacciones
- Tamaño del bloque
- Tarifa promedio de transacción
- Tiempo de confirmación
- Otros detalles relevantes extraídos de la web

## Tecnologías Utilizadas

- **Lenguaje:** Python
- **Librerías:** BeautifulSoup, Requests, Pandas
