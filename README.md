# ⚛️ Computación Cuántica — Laboratorios

**Autora:** Karla Beatriz Rojas Chimal  
**Curso:** Computación Cuántica  
**Herramientas principales:** [Qiskit](https://www.ibm.com/quantum/qiskit) · Python 3.11 · Jupyter Notebooks

---

## 📋 Descripción

Este repositorio contiene los laboratorios prácticos del curso de **Computación Cuántica**, donde se exploran los fundamentos de la computación cuántica mediante simulaciones y circuitos cuánticos usando la librería **Qiskit** de IBM.

---

## 🗂️ Contenido

| Archivo | Descripción |
|---|---|
| `Lab1_Introduccion.ipynb` | Introducción a Qiskit: qubits, compuertas básicas y medición |
| `LAB1_Introduccion_RojasChimal_KarlaBeatriz.ipynb` | Entrega del Lab 1 |
| `Lab2_Sistemas_Multi_Qubits__resueltoclase.ipynb` | Sistemas de múltiples qubits, entrelazamiento y circuitos compuestos (resuelto en clase) |
| `LAB2_Sistemas_RojasChimal_KarlaBeatriz.ipynb` | Entrega del Lab 2 |
| `Lab3_Algoritmos_Cuánticos1(original).ipynb` | Algoritmos cuánticos: Deutsch-Jozsa, Bernstein-Vazirani, Simon (plantilla original) |
| `Lab3_Algoritmos_Cuánticos__Resueltoclase.ipynb` | Algoritmos cuánticos resueltos en clase |
| `environment.yml` | Entorno Conda con todas las dependencias del curso |

---

## 🚀 Configuración del entorno

### Requisitos previos
- [Anaconda](https://www.anaconda.com/download) o [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- Python 3.11+

### Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/KarlaRoChi/Compu-Cuantica.git
   cd Compu-Cuantica
   ```

2. Crea el entorno Conda desde el archivo `environment.yml`:
   ```bash
   conda env create -f environment.yml
   ```

3. Activa el entorno:
   ```bash
   conda activate compu_cuantica
   ```

4. Registra el kernel de Jupyter:
   ```bash
   python -m ipykernel install --user --name compu_cuantica --display-name "Python (Compu Cuántica)"
   ```

5. Abre Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## 📦 Dependencias principales

| Librería | Uso |
|---|---|
| `qiskit` | Construcción y simulación de circuitos cuánticos |
| `qiskit-ibm-runtime` | Ejecución en hardware real de IBM Quantum |
| `numpy` | Álgebra lineal y operaciones numéricas |
| `matplotlib` | Visualización de circuitos y resultados |
| `scipy` | Funciones matemáticas avanzadas |
| `sympy` | Álgebra simbólica |
| `pylatexenc` | Renderizado LaTeX en visualizaciones de Qiskit |

---

## 🧪 Temas cubiertos

- 🔹 **Lab 1 — Introducción:** Qubits, superposición, compuertas Hadamard, Pauli-X/Y/Z, medición
- 🔹 **Lab 2 — Sistemas Multi-Qubit:** Producto tensorial, entrelazamiento cuántico, estados de Bell, circuitos de múltiples qubits
- 🔹 **Lab 3 — Algoritmos Cuánticos:** Algoritmo de Deutsch-Jozsa, Bernstein-Vazirani, algoritmo de Simon

---

## 📄 Licencia

Este repositorio es de uso académico. Todos los derechos pertenecen a la autora.
