# 📚 Estructura de Datos — APE 02

Práctica académica enfocada en el análisis y la comparación de
métodos de lectura de archivos en JavaScript utilizando Node.js.

---

## 📌 Información general

| **Detalle** | **Descripción** |
|:---|:---|
| 📘 Asignatura | Estructura de Datos |
| 📝 Práctica | N.º 02 |
| 👨‍🏫 Docente | Cristian Ramiro Narváez Guillén |
| 💻 Tecnología | JavaScript y Node.js |
| 🛠️ Editor | Visual Studio Code |

---

## 👥 Integrantes del grupo

| **N.º** | **Nombre del integrante** |
|:---:|:---|
| 1 | Valeria Agila |
| 2 | Pilar Naranjo |
| 3 | Jose Valencia |
| 4 | Alison Tapia |
| 5 | Roy Gordillo |

---

## 🎯 Objetivo

Implementar programas en JavaScript mediante Node.js para generar y procesar archivos, comparando la lectura síncrona y la lectura asíncrona mediante Streams, con el propósito de analizar el tiempo de ejecución y el consumo de memoria.

## 📂 Archivos del proyecto

El repositorio contendrá los siguientes programas:

| Archivo | Descripción |
|---|---|
| `lab02_generador.js` | Genera un archivo CSV con un millón de coordenadas geográficas. |
| `lab02_lectura_sync.js` | Lee el archivo CSV de forma síncrona y mide el tiempo de ejecución y el consumo de memoria. |
| `lab02_lectura_stream.js` | Procesa el archivo CSV mediante Streams y registra las métricas de ejecución. |

## 🛠️ Requisitos

- Node.js 20.x o superior.
- Visual Studio Code.
- Git.

## 🚀 Ejecución

Ejecutar los programas en el siguiente orden desde la terminal:

**1. Generar los datos**

```bash
node lab02_generador.js
```

**2. Realizar la lectura síncrona**

```bash
node lab02_lectura_sync.js
```

**3. Realizar la lectura mediante Streams**

```bash
node lab02_lectura_stream.js
```

El primer programa genera el archivo `coordenadas_masivas.csv`, que será utilizado por los dos programas de lectura.

## 🌿 Trabajo colaborativo

El proyecto se gestionará mediante Git y GitHub, utilizando ramas para facilitar el trabajo colaborativo. Cada integrante podrá trabajar en su propia rama y registrar los cambios realizados mediante commits.