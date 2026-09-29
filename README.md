# Qiskit · Semillero en Computación Cuántica

Material de trabajo del **Semillero en Computación Cuántica** de la Universidad del Rosario
para aprender computación cuántica con [Qiskit](https://www.ibm.com/quantum/qiskit), el kit de
desarrollo de código abierto de IBM para construir, simular y ejecutar circuitos cuánticos.

## 📓 Notebooks

| # | Notebook | Tema | Abrir |
|---|---|---|---|
| 01 | [`01_nombre.ipynb`](notebooks/01_nombre.ipynb) | [Tema del notebook] | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/semillero-computacion-cuantica-urosario/Qiskit/blob/main/notebooks/01_nombre.ipynb) |

## ⚙️ Requisitos

- Python 3.10 o superior
- `qiskit` y `qiskit-aer` (simulador local)
- `matplotlib` y `pylatexenc` (para dibujar circuitos)

```bash
pip install qiskit qiskit-aer matplotlib pylatexenc
```

> ⚠️ Qiskit cambia su API con frecuencia entre versiones mayores. Cada notebook indica
> la versión con la que fue probado; si aparece un error de importación, revisa esa versión.

La forma más fácil de empezar es abrir el notebook en Google Colab con el botón de la tabla.

## 🤝 Cómo contribuir

1. Crea una rama (o un *fork*) a partir de `main`.
2. Agrega o mejora un notebook siguiendo la convención `NN_tema.ipynb` dentro de `notebooks/`.
3. Antes de hacer *commit*, reinicia el kernel, ejecuta todo y limpia las salidas pesadas.
4. Abre un *pull request* explicando qué cambiaste y por qué.

## 📚 Recursos

- [Documentación de Qiskit](https://docs.quantum.ibm.com)
- [IBM Quantum Learning](https://learning.quantum.ibm.com)
- Nielsen y Chuang, *Quantum Computation and Quantum Information*, Cambridge University Press.
