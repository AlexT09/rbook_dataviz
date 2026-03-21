--- 
title: "Análisis Exploratorio de Datos Sísmicos"
author: "Alex Teran & Eliasb Pajaro"
date: "2026-03-21"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib]
description: |
  Análisis Exploratorio de Datos (EDA) aplicado al conjunto de datos
  sísmicos NGACOL, incluyendo visualización estática, estadísticas de
  resumen, correlaciones y distribución espacial de eventos.
link-citations: yes
---

# Prefacio {-}

Este libro presenta un **Análisis Exploratorio de Datos (EDA)** aplicado
al conjunto de datos sísmicos **NGACOL**, que reúne registros de
aceleración del suelo provenientes de la base de datos norteamericana
NGAW2 y de eventos sísmicos en Colombia.

El EDA se desarrolla siguiendo el flujo iterativo propuesto en el
Capítulo 3 del curso:

1. Generar preguntas sobre los datos
2. Buscar respuestas mediante visualización, transformación y estadísticas
3. Refinar las preguntas o generar nuevas

## Preguntas iniciales {-}

- ¿Cómo se distribuye la aceleración sísmica?
- ¿Existe relación entre distancia a la ruptura y aceleración?
- ¿Influye el tipo de suelo en la aceleración registrada?
- ¿Existe variación espacial en los registros?
- ¿La variable sigue un comportamiento log-normal?
- ¿Existen diferencias entre los registros de origen NGAW2 y Colombia?
