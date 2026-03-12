---
type: moc
area: roadmap
status: activo
nivel_objetivo: profesional
---

```dataview
TABLE length(rows) AS "Total Notas"
FROM "Estudios"
WHERE !contains(file.folder, "99_MAPAS")
 AND !contains(file.folder, "Excalidraw")
 AND !contains(file.folder, "Templates")
GROUP BY file.folder AS Carpeta
```

# 🧠 ROADMAP PROFESIONAL — Ingeniería de Software / Computer Science

> **Objetivo**: Dominio estructural, no superficial.
> **Meta**: Nivel profesional por encima del promedio.

---

# 🔵 FASE 1 — Fundamento Computacional Base

## 📁 00_FUNDAMENTOS
- [[00. Glosario]]
- [[02. Binario y Lógica]]
- [[03. Variables y Tipos de Datos]]
- [[04. Operadores y Expresiones]]
- [[05. Estructuras de Control]]
- [[06. Funciones y Modularización]]
- [[08. Pensamiento Algorítmico]]
- [[01. Anatomía de la Programación]]
- [[09. Modelos de Ejecución]]
- [[10. Compilado vs. Interpretado]]
- [[07. Abstracción]]

### 🎯 Resultado esperado:
Entender qué es programar sin depender de un lenguaje.

---

# 🟣 FASE 2 — Representación y Capa de Sistema

## 📁 06_SISTEMAS
- [[07. Representación de Enteros]]
- [[08. IEEE 754]]
- [[09. Endianness]]
- [[10. Codificación de Texto]]
- [[02. Sistemas Operativos]]
- [[04. Arquitectura de Computadoras]]

## 📁 01_COMPUTER_SCIENCE / Fundamentos Teóricos
- [[02. Stack vs. Heap (Control de Memoria Profunda)]]
- [[03. Representación de Datos Complejos]]

### 🎯 Resultado esperado:
Comprender qué ocurre debajo del código.

---

# 🟢 FASE 3 — Matemática Formal Aplicada

## 📁 10_MATEMATICAS
- [[02. Lógica Proposicional]]
- [[03. Lógica de Predicados]]
- [[04. Teoría de Conjuntos]]
- [[01. Matemática Discreta]]
- [[09. Análisis básico de crecimiento]]
- [[08. Matemática para Algoritmos]]

### 🎯 Resultado esperado:
Capacidad de razonar formalmente y entender complejidad.

---

# 🔴 FASE 4 — Fundamentos Teóricos de Computación

## 📁 01_COMPUTER_SCIENCE / Fundamentos Teóricos
- [[22. Recursión]]
- [[01. Modelos de Computación]]

### Dentro de Modelos:
- [[01. Máquina de Turing]]
- [[02. RAM Model]]
- [[03. Church-Turing Thesis]]

## 📁 01_COMPUTER_SCIENCE / Complejidad Algorítmica
- [[15. Complejidad Algorítmica]]
- [[16. Notación Big-O]]

### 🎯 Resultado esperado:
Entender qué es computable y qué es eficiente.

---

# 🟡 FASE 5 — Estructuras de Datos y Diseño de Algoritmos

## 📁 Estructuras de Datos
- [[05. Arreglos]]
- [[09. Grafos]]
- [[11. Árboles]]
- [[10. Tablas Hash]]
- [[12. Árboles → Heaps]]
- [[13. Árboles → Tries]]

## 📁 Diseño de Algoritmos
- [[18. Algorítmos de Búsqueda]]
- [[17. Algoritmos de Ordenamiento]]
- [[21. Divide AND Conquer]]
- [[23. Programación dinámica]]

### 🎯 Resultado esperado:
Resolver problemas complejos con criterio estructural.

---

# 🟠 FASE 6 — Ingeniería Profesional

## 📁 02_INGENIERIA_SOFTWARE
- [[01. Ciclo de Vida del Software (SPDC)]]
- [[02. Ingeniería de Requerimientos]]
- [[03. UML y Modelado]]
- [[04. Gestión de Proyectos]]
- [[05. Git y Control de Versiones]]
- [[06. Testing]]
- [[07. Clean Code]]
- [[08. Refactorización]]
- [[09. Principios SOLID]]
- [[10. DRY-KISS-YAGNI]]
- [[11. Patrones Básicos]]
- [[12. Metodologías (Scrum)]]
- [[13. Estimación de Costos y Tiempos]]
- [[14. Ética Profesional y Legal]]
- [[15. Manejo de Errores (Debugging)]]

### 🎯 Resultado esperado:
Capacidad de trabajar en equipo profesional.

---

# 🔵 FASE 7 — Especialización Técnica

## Web
- [[03_MOC Web]]

## Backend
- [[04_MOC BackEnd]]

## Arquitectura
- [[05_MOC Arquitectura]]

## Sistemas
- [[06_MOC Sistemas]]

## DevOps_Cloud
- [[07_MOC DevOps_Cloud]]

## Seguridad
- [[08_MOC Seguridad]]

## Datos
- [[09_MOC Datos]]

---

# 🧠 FASE 8 — Potenciador Moderno

## 📁 12_PROMPT_ENGINEERING
- [[01. Fundamentos del Modelo de Lenguaje]]
- [[02. Prompt Engineering básico]]
- [[03. Prompt Engineering avanzado]]
- [[04. Chain of Thought]]
- [[05. RAG (Retrieval-Augmented Generation)]]
- [[06. Evaluación de Respuestas]]
- [[07. Automatización con IA]]
- [[08. Ética y Sesgos en IA]]

### 🎯 Resultado esperado:
Aumentar productividad cognitiva con IA.

---

# 🧩 FASE TRANSVERSAL — Soft Skills (Siempre Activa)

## 📁 13_SOFT_SKILLS
- [[01. Comunicación Técnica]]
- [[02. Documentación Profesional]]
- [[03. Pensamiento Crítico]]
- [[04. Resolución de Conflictos en Equipo]]
- [[05. Gestión del Tiempo]]
- [[06. Negociación Técnica]]
- [[07. Feedback y Code Review]]
- [[08. Presentación de Proyectos]]
- [[09. Mentalidad de Crecimiento Profesional]]
- [[10. Ética y Responsabilidad Profesional (Ampliado)]]

---

# 🔥 REGLA ESTRATÉGICA

No avanzar de fase hasta poder:
- Explicar los conceptos sin notas.
- Conectar al menos 3 notas entre sí.
- Resolver ejercicios prácticos.

---
