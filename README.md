# TP3 — Visión por Computadora I

**Carrera de Especialización en Inteligencia Artificial (CEIA)**

**Integrantes:** Gaspar Rivollier · Mariel Gaitan

---

## Descripción

Trabajo práctico N°3 de Visión por Computadora I. El objetivo es detectar el logo de Coca-Cola en un conjunto de imágenes utilizando técnicas clásicas de procesamiento de imágenes y descriptores de características.

## Trabajo práctico

El notebook principal (`notebooks/tp3_cv.ipynb`) contiene la implementación de la solución.

## Estructura del repositorio

```
├── assets/
│   ├── images/          # Imágenes de prueba (con y sin logo)
│   └── template/        # Template del logo (pattern.png)
├── notebooks/
│   ├── tp3_cv.ipynb               # Notebook principal con la solución
│   └── tp3_cv_experiments.ipynb   # Notebook de experimentación
├── pyproject.toml
├── LICENSE
└── README.md
```
## Dependencias

- Python ≥ 3.13
- OpenCV (`opencv-python`)
- NumPy
- Matplotlib
- supervision
- scikit-image

### Instalación

```bash
uv sync
```

## Licencia

[MIT](LICENSE)