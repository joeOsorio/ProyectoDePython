# Proyecto de Análisis de Texto en Python

## Descripción

Este proyecto es una aplicación de análisis de texto desarrollada en Python 3.12.2, diseñada para identificar y gestionar anagramas, así como realizar diversas operaciones relacionadas con la frecuencia de palabras en archivos de texto. La aplicación ofrece una interfaz de menú interactivo que permite al usuario explorar diferentes funcionalidades de manera sencilla y eficiente.

## Motivación

La idea de este proyecto surgió del interés en entender cómo diferentes sistemas son capaces de analizar texto de manera rápida y eficiente. El desafío radica en la complejidad del problema de los anagramas, algo que me resultó especialmente difícil en el semestre anterior. Este proyecto no solo me ha ayudado a profundizar mis conocimientos en Python, sino que también representa un hito personal en mi desarrollo como programador.

## Características Principales

- **Detección de Anagramas**: Encuentra y muestra todas las palabras que son anagramas en el texto analizado.
- **Top N Palabras**: Muestra las N palabras más frecuentes en el texto.
- **Palabras Repetidas y Únicas**: Identifica y muestra las 5 palabras más repetidas y las 5 palabras menos repetidas.
- **Búsqueda de Palabras**: Permite buscar palabras específicas en el texto.
- **Generación de Informes**: Crea informes detallados sobre la frecuencia y características de las palabras en el archivo de texto.

## Tecnologías Utilizadas

- Python 3.12.2
- Librerías: `re`, `collections.Counter`, `shutil`, `termcolor`, `prettytable`

## Instalación

Para ejecutar este proyecto, es necesario tener Python 3.12.2 instalado junto con las siguientes librerías:

```bash
pip install termcolor prettytable
