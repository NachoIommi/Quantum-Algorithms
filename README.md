⚛️ Algoritmos Cuánticos Fundamentales con Qiskit

Este repositorio contiene una colección de implementaciones prácticas y análisis teóricos de los algoritmos más importantes en la computación cuántica. El material está basado en las lecciones de "Understanding Quantum Information and Computation" de John Watrous (IBM).

El objetivo de este proyecto es servir como una guía integral que combina la teoría matemática con la ejecución real de circuitos cuánticos utilizando el framework Qiskit de IBM.

📂 Contenido del Repositorio

📘 Parte 1: Algoritmos de Consulta (Query Algorithms)

Demostración de la ventaja cuántica en problemas de oráculo (caja negra).

Algoritmo de Deutsch: Determina si una función de 1 bit es constante o balanceada en una sola consulta.

Algoritmo de Deutsch-Jozsa: Generalización a $n$ bits, mostrando separación exponencial determinista.

Algoritmo de Bernstein-Vazirani: Encuentra una cadena oculta en una sola consulta.

Algoritmo de Simon: Demostración de ventaja exponencial probabilística mediante la búsqueda de periodos ocultos.

📙 Parte 2: Fundamentos Algorítmicos

Construcción de bloques básicos para computación compleja.

Lógica Reversible: Implementación de compuertas Toffoli y simulación de lógica clásica (AND, OR).

Uncomputing: Técnica de limpieza de qubits ancilla para preservar la interferencia cuántica.

📗 Parte 3: Estimación de Fase y Factorización

El corazón de la criptografía cuántica.

Transformada Cuántica de Fourier (QFT): Implementación recursiva del cambio de base.

Estimación de Fase Cuántica (QPE): Algoritmo genérico para encontrar autovalores.

Algoritmo de Shor: Implementación completa para la búsqueda de orden (Order Finding), paso clave para factorizar enteros.

📕 Parte 4: Búsqueda No Estructurada

Algoritmo de Grover: Búsqueda en bases de datos no ordenadas con ventaja cuadrática. Incluye la construcción del oráculo de fase y el operador de difusión.

📄 Documentación

Compendio_Teorico.md: Un resumen exhaustivo de la teoría matemática y lógica detrás de cada algoritmo.

🚀 Requisitos e Instalación

Para ejecutar los notebooks, necesitas tener instalado Python y las librerías de Qiskit.

Clona este repositorio:

git clone  https://github.com/NachoIommi/Quantum-Algorithms.git
cd NOMBRE_DEL_REPO


Crea un entorno virtual (opcional pero recomendado):

python -m venv qiskit_env
source qiskit_env/bin/activate  # En Windows: qiskit_env\Scripts\activate


Instala las dependencias:

pip install qiskit qiskit-aer matplotlib jupyter


🛠️ Uso

Abre los archivos .ipynb en Jupyter Notebook o Visual Studio Code para ver el código, los diagramas de circuitos y los resultados de las simulaciones.

# Ejemplo de ejecución en terminal
jupyter notebook


📚 Referencias

Watrous, J. (IBM Quantum Learning). Understanding Quantum Information and Computation.

Documentación oficial de Qiskit.

Este proyecto fue realizado con fines educativos para consolidar conocimientos en computación cuántica.
