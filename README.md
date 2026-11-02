# Riemann Geometry & Deep Learning (`riemann-geometry-dl`)

Este repositorio contiene experimentos, modelos y código de investigación del post de Substask ["¿Cómo afecta la geometría a los modelos de Deep Learning?"](https://cesarzammar.substack.com/p/como-afecta-la-geometria-a-los-modelos?r=2iqk5m) centrados en la aplicación de la **Geometría Riemannaniana** a Deep Learning. El proyecto utiliza la suite de herramientas de Python basadas en [`uv`](https://github.com/astral-sh/uv) para un manejo eficiente de entornos virtuales y dependencias.

---

## 🛠️ Requisitos Previos

* **Python 3.11+**
* [**`uv`**](https://github.com/astral-sh/uv) instalado en el sistema.

---

## 🚀 Instalación y Configuración

El proyecto está configurado para gestionar automáticamente el entorno virtual y las dependencias utilizando el `Makefile` y `pyproject.toml`.

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/riemann-geometry-dl.git
   cd riemann-geometry-dl
   ```

2. **Crear el entorno virtual e instalar dependencias:**
   ```bash
   make setup
   ```
   *Esto creará el entorno `.venv` e instalará las librerías necesarias mediante `uv sync`.*

---

## 📂 Estructura del Proyecto

```text
riemann-geometry-dl/
├── Makefile              # Comandos de automatización para uv y jupyter
├── pyproject.toml        # Configuración del proyecto y dependencias
├── uv.lock               # Archivo de bloqueo de dependencias
├── notebooks/            # Notebooks de Jupyter para experimentación
└── README.md             # Documentación principal del proyecto
```

---

## 🧹 Limpieza

Para eliminar el entorno virtual generado y los archivos de caché:

```bash
make clean
```