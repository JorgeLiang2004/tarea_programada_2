---
title: "Tarea Programada 2 - Análisis de Vuelos NYC 2013"
author: "Jorge Liang"
date: "2026-06-04"
output: html_document
---

```{r setup, include=FALSE}
# Cargar bibliotecas
library(nycflights13)
library(dplyr)
library(ggplot2)
library(tidyr)
library(lubridate)
library(DT)
```

# 1. Carga y exploración de datos

```{r}
# Cargar las 5 tablas del paquete nycflights13
data("flights")
data("airlines")
data("airports")
data("planes")
data("weather")

# Mostrar primeras filas de flights
head(flights, 10)
```

```{r}
# Ver estructura de flights
glimpse(flights)
```