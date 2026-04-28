# Actividad: Propuesta de Práctica Temática de Sistemas (Enfoque en Documentación)

## 1) Título de la práctica

**Propuesta base sugerida:** **“Asistente de Estudio en Terminal”**

> Si lo prefieres, puedes cambiar el título por otro igual de claro y pequeño, por ejemplo:
> - Mini Toolkit en ARM64
> - Reporteador de Información del Sistema
> - Organizador de Archivos
> - Juego de Aprendizaje en Línea de Comandos

---

## 2) Descripción general

En esta actividad vas a **diseñar una propuesta de proyecto pequeño** para una práctica temática de arquitectura/computación de sistemas.

Tu propuesta debe partir de una idea simple, viable y útil, y tú vas a definir:
- qué problema resuelve,
- para quién,
- cómo se organizará el repositorio,
- y cómo validarás su funcionamiento con pruebas básicas.

### Lenguaje principal (elige solo uno)
- ARM64 Assembly
- C
- Python
- Bash

> **Nota importante sobre ARM64 Assembly:** úsalo únicamente si tu programa será **muy pequeño** (alcance acotado, pocas funciones y flujo simple).

### Enfoque de la actividad
La prioridad de esta entrega es la **documentación y planeación**. Antes de programar mucho, debes justificar claramente la idea, su alcance y su estructura.

### Restricciones de alcance
Para mantener la práctica compatible con uso académico y herramientas con límites de uso:
- El proyecto debe ser **pequeño**.
- Evita frameworks pesados.
- No uses APIs pagadas.
- No uses bases de datos.
- No uses servicios en la nube.
- No uses contenedores.
- Evita dependencias complejas o difíciles de instalar.

---

## 3) Entregables del estudiante

Tu repositorio debe incluir **como mínimo** los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

También puedes incluir (opcional):
- `src/`
- `scripts/`
- `tests/`

### Contenido esperado por archivo

#### `README.md`
Incluye:
- Nombre de la práctica.
- Objetivo general (2–4 líneas).
- Lenguaje elegido y justificación breve.
- Instrucciones mínimas para ejecutar (si ya hay código).
- Enlace o referencia a la carpeta `docs/`.

#### `docs/propuesta.md`
Incluye:
- Título final del proyecto.
- Problema u oportunidad que atiende.
- Objetivo general y 2–3 objetivos específicos.
- Alcance (qué sí incluye y qué no incluye).
- Tecnologías/herramientas (solo las necesarias).
- Estimación de tamaño (pequeño) y por qué es viable.

#### `docs/caso_de_uso.md`
Incluye:
- Usuario objetivo.
- Escenario de uso principal.
- Entradas esperadas.
- Salidas esperadas.
- Ejemplo narrado paso a paso de uso.

#### `docs/estructura_repositorio.md`
Incluye:
- Árbol del repositorio propuesto.
- Propósito de cada carpeta y archivo principal.
- Convenciones de nombres (archivos, scripts, pruebas).

#### `docs/plan_de_pruebas.md`
Incluye:
- Lista de al menos 5 casos de prueba.
- Para cada caso: entrada, procedimiento, salida esperada, criterio de éxito.
- Pruebas de casos válidos y al menos 1 caso de error.

---

## 4) Estructura recomendada del repositorio

Usa como base esta estructura mínima:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> `<ext>` depende de tu lenguaje:
> - `S` (ARM64 Assembly)
> - `c` (C)
> - `py` (Python)
> - `sh` (Bash, si decides que el archivo principal sea script)

---

## 5) Instrucciones de desarrollo

1. Define una idea de práctica que puedas implementar en pequeño.
2. Selecciona un único lenguaje principal.
3. Redacta toda la documentación solicitada en `docs/`.
4. (Opcional) Agrega una versión mínima funcional en `src/`.
5. Asegúrate de que tu propuesta sea entendible para cualquier compañero del curso.

---

## 6) Criterios de evaluación sugeridos

- **Claridad de la propuesta (25%)**: problema, objetivo y alcance bien definidos.
- **Calidad de documentación (30%)**: estructura, redacción técnica y coherencia entre archivos.
- **Viabilidad técnica (20%)**: proyecto pequeño, sin complejidad innecesaria.
- **Diseño del repositorio (15%)**: organización limpia y mantenible.
- **Plan de pruebas (10%)**: casos completos, medibles y realistas.

---

## 7) Recomendaciones finales

- Empieza simple: una sola funcionalidad principal bien explicada vale más que muchas incompletas.
- Si usas ARM64 Assembly, reduce alcance al mínimo indispensable.
- Evita “scope creep” (crecer el proyecto sin control).
- Si usas IA de apoyo, úsala para acelerar borradores, pero valida técnicamente cada decisión.

---

## 8) Entrega

Sube tu trabajo en el repositorio asignado en GitHub Classroom con todos los archivos solicitados.

**Fecha de entrega:** _(definida por tu docente)_
