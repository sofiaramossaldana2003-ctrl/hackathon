# Estructura del Proyecto: Datasets

Este documento detalla la estructura de los datos utilizados en este proyecto para garantizar la integridad y la reproducibilidad de los modelos.

## 1. Inventario de Datasets
La fuente de verdad absoluta para este proyecto son los archivos `.csv` proporcionados por **renzocollins**.

| Nombre del Archivo | Propósito | Ubicación en el Repositorio |
| :--- | :--- | :--- |
| `dataset_clientes.csv` | Perfil y comportamiento del cliente (base para features y scoring). | `data/raw/` |
| `historial_campanias.csv` | Histórico de ofertas, canales y respuestas (entrenamiento). | `data/raw/` |
| `catalogo_ofertas_entrega.csv` | Catálogo generalizable de ofertas (incluye MT y portafolio). | `data/raw/` |

## 2. Documentación
*   **Diccionario de Datos:** `docs/diccionario_datos_participantes.docx`
    *   *Nota:* Es **obligatorio** leer este documento antes de procesar los datos; define el significado técnico de cada columna.

---
