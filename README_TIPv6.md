# 🛡️ TIPv6 -- Threat Intelligence Platform

Trabajo Fin de Máster -- Universidad Complutense de Madrid\
Máster en Ciberseguridad Defensiva y Ofensiva (Curso 2025--2026)

------------------------------------------------------------------------

## 📌 Descripción

TIPv6 es un prototipo funcional de plataforma de inteligencia de
amenazas desarrollado como TFM. Implementa un pipeline secuencial que
permite:

-   Identificación estructural del objetivo
-   Enriquecimiento OSINT
-   Generación de amenazas y remediaciones
-   Correlación y scoring de riesgo
-   Generación de informe final en PDF

------------------------------------------------------------------------

## 🧩 Pipeline

1.  Identify\
2.  OSINT (Step220)\
3.  Mitigations (Step310)\
4.  Scoring (Step410)\
5.  Report PDF

------------------------------------------------------------------------

## ⚙️ Requisitos

-   Windows 11
-   PowerShell 7
-   Python 3.12.x
-   Conexión a Internet

### Instalar PowerShell 7

winget install --id Microsoft.Powershell --source winget

### Instalar Python 3.12

https://www.python.org/downloads/release/python-31212/

------------------------------------------------------------------------

## 📦 Instalación

Extraer proyecto en:

C:`\TIP6`{=tex}

Ejecutar:

TIP6_START_ALL.cmd

------------------------------------------------------------------------

## 🌐 Web

cd C:`\TIP6`{=tex} python -u app.py

Abrir:

http://127.0.0.1:5000

------------------------------------------------------------------------

## ▶️ Lanzador

Seleccionar opción 1. Introducir objetivo (dominio/IP).

Ejemplo generado:

Target: www.elpais.com\
RunId: run-id-20260219_172519\
RunDir: C:`\TIP6`{=tex}`\ANALIZADOS`{=tex}`\Caso`{=tex}-XXXX

------------------------------------------------------------------------

## 📄 Informe

Se genera PDF con:

-   Resumen ejecutivo
-   Señales OSINT
-   Amenazas
-   Score
-   Remediación

------------------------------------------------------------------------

Autora: Indibg\
Generado el 2026-02-19
