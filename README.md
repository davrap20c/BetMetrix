# BetMetrix
📊 BetMetrix: Plataforma web integradora de cuotas en tiempo real (1X2) y estadísticas deportivas avanzadas. Arquitectura híbrida basada en APIs REST y Web Scraping con un modelo de datos global (GCS).

# BetMetrix ⚽📈

[cite_start]**BetMetrix** es un sistema de información diseñado para aficionados al deporte y analistas que buscan optimizar sus pronósticos deportivos mediante un ecosistema unificado[cite: 49, 53]. [cite_start]A diferencia de los comparadores tradicionales, nuestra plataforma cruza cuotas de múltiples casas de apuestas con factores estadísticos clave en una única interfaz gráfica[cite: 54, 55].

## 🚀 Características Principales
* [cite_start]**Comparador de Cuotas**: Integración en tiempo real del mercado "Ganador del partido" (1X2) de al menos tres casas de apuestas[cite: 59].
* [cite_start]**Contexto Estadístico**: Visualización de rachas de victorias/derrotas y partes de lesiones para decisiones informadas[cite: 60, 81].
* [cite_start]**Arquitectura Híbrida**: Consultas en tiempo real para cuotas y procesamiento por lotes (*batch*) para datos estadísticos históricos[cite: 137].
* [cite_start]**Modelo de Datos Global (GCS)**: Unificación de fuentes heterogéneas bajo un esquema conceptual global único en el servidor[cite: 61, 109].

## 🛠️ Stack Tecnológico
* [cite_start]**Backend**: Java / Google App Engine[cite: 114].
* [cite_start]**Base de Datos**: PostgreSQL / Cloud SQL (Modelo Relacional para GCS)[cite: 128].
* **Extracción de Datos**:
    * [cite_start]**APIs**: The Odds API (Cuotas JSON) y API-Football (Estadísticas REST)[cite: 79, 80].
    * [cite_start]**Web Scraping**: Extracción de datos de Transfermarkt y BeSoccer[cite: 81, 108].
* [cite_start]**Despliegue**: Google Cloud Platform (Arquitectura Cloud nativa)[cite: 128, 186].

## 📐 Arquitectura
[cite_start]El sistema sigue el modelo de **Vistas 4+1** para garantizar un diseño robusto y escalable[cite: 297]:
1. **Vista Lógica**: Separación clara entre el Motor de Integración, el módulo de Scraping y el cliente de APIs.
2. [cite_start]**Estrategia de Datos**: Implementación de un flujo de integración que resuelve la heterogeneidad de nombres y formatos entre proveedores[cite: 112].
3. [cite_start]**Despliegue**: Infraestructura elástica en la nube para soportar picos de demanda durante jornadas deportivas[cite: 187].

## 📋 Requisitos del Proyecto
[cite_start]Este proyecto se desarrolla bajo la normativa de la asignatura *Ingeniería de Sistemas de Información* (ISI) de la Universidad de Granada[cite: 96, 155]:
* [cite_start]Integración de un mínimo de 3 fuentes de datos heterogéneas[cite: 107].
* [cite_start]Uso obligatorio de al menos una API estándar y una fuente mediante Web Scraping[cite: 108].
* [cite_start]Procesamiento necesariamente realizado en el servidor para el sistema de integración[cite: 117].

## 👥 Autores
* [cite_start]**Iván Martín Alonso** [cite: 50]
* [cite_start]**David Pérez Capilla** [cite: 51]

---
[cite_start]*Este proyecto es parte del curso académico 2025-2026 del Departamento de Ciencias de la Computación e Inteligencia Artificial (DECSAI) de la UGR[cite: 17, 97].*
