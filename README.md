# Tutoría Fácil UTA

Prototipo web interactivo desarrollado para la asignatura **Interacción Humano Computador (IHC)** de la Universidad Técnica de Ambato.

El proyecto propone una interfaz adaptable para facilitar la gestión de tutorías académicas, permitiendo al estudiante consultar disponibilidad, reservar una tutoría, revisar la información antes de confirmar y reprogramar una cita cuando sea necesario.

---

## Objetivo

Diseñar y evaluar una solución interactiva que permita a los estudiantes gestionar tutorías académicas mediante un flujo sencillo, comprensible y accesible.

El diseño busca reducir errores durante la reserva, mantener visible el estado del sistema y proporcionar retroalimentación clara durante cada etapa de la interacción.

---

## Funcionalidades

El prototipo permite:

- Consultar docentes y asignaturas.
- Seleccionar una fecha para la tutoría.
- Visualizar horarios disponibles y ocupados.
- Seleccionar un horario disponible.
- Revisar la información antes de confirmar.
- Confirmar una tutoría.
- Obtener un código de reserva.
- Consultar las tutorías registradas.
- Reprogramar una tutoría.
- Acceder a una sección de ayuda.
- Utilizar la interfaz desde diferentes tamaños de pantalla.

---

## Flujo principal

El flujo principal de interacción es:

```text
Inicio
   ↓
Selección de docente
   ↓
Selección de fecha
   ↓
Selección de horario
   ↓
Revisión
   ↓
Confirmación
   ↓
Tutoría confirmada
```

Después de confirmar una tutoría, el estudiante puede acceder a **Mis tutorías** y seleccionar la opción de **Reprogramar**.

---

## Interacción Humano Computador

Durante el diseño del prototipo se consideraron principios y conceptos de IHC orientados a mejorar la comprensión y facilidad de uso de la interfaz.

### Heurísticas de Nielsen

Se consideraron aspectos como:

- Visibilidad del estado del sistema.
- Correspondencia entre el sistema y el mundo real.
- Control y libertad del usuario.
- Consistencia.
- Prevención de errores.
- Reconocimiento antes que recuerdo.
- Diseño estético y minimalista.
- Ayuda y orientación al usuario.

### Leyes de Gestalt

La interfaz aplica principios como:

- Proximidad.
- Similitud.
- Continuidad.
- Figura y fondo.
- Región común.

Estos principios permiten organizar visualmente los elementos relacionados y facilitar la interpretación de la interfaz.

---

## Accesibilidad

El prototipo considera los principios **POUR**:

- **Perceptible:** los estados y contenidos principales son visualmente diferenciables.
- **Operable:** los controles interactivos pueden utilizarse de forma clara y se consideran estados de foco.
- **Comprensible:** las acciones utilizan etiquetas directas y mantienen un flujo consistente.
- **Robusto:** se utiliza HTML semántico y atributos de accesibilidad para mejorar la interpretación de la interfaz.

También se incorporaron elementos como:

- Enlace para saltar al contenido principal.
- Etiquetas asociadas a los controles.
- Estados accesibles para fechas y horarios.
- Horarios ocupados deshabilitados.
- Información textual además de indicadores visuales.
- Retroalimentación durante la selección.
- Diseño responsive.

---

## Prueba cruzada

Se realizó una prueba del prototipo con una persona perteneciente a otro equipo.

La tarea solicitada fue:

> Reservar una tutoría para el jueves y luego cambiar el horario.

### Resultados

| Criterio | Resultado |
|---|---|
| Completó la tarea | Sí |
| Tiempo | 55 segundos |
| Necesitó ayuda | No |
| Errores observados | Ninguno |
| Dudas observadas | Ninguna |
| Comentario | La interfaz parecía visualmente muy simple |

El participante encontró fácilmente las acciones necesarias para completar la tarea.

---

## Iteración del prototipo

A partir del comentario obtenido durante la prueba cruzada, se realizó una iteración enfocada en mejorar la presentación visual.

Se conservaron el flujo, las etiquetas y la ubicación de las acciones principales debido a que el participante completó la tarea correctamente, sin ayuda y sin presentar errores o dudas.

Entre las mejoras realizadas se encuentran:

- Mayor jerarquía visual.
- Mejora de la identidad cromática.
- Mayor diferenciación entre tarjetas y secciones.
- Incorporación de sombras y profundidad.
- Mejora del espaciado.
- Mayor diferenciación de las acciones principales.
- Mejor adaptación a dispositivos móviles.

Las evidencias del antes y después se encuentran en:

```text
evidencias/
├── antes_iteracion.png
└── despues_iteracion.png
```

---

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- Git
- GitHub
- Visual Studio Code

El prototipo no requiere frameworks ni dependencias externas.

---

## Ejecución del proyecto

### Opción 1: abrir directamente

1. Descargar o clonar el repositorio.
2. Abrir la carpeta del proyecto.
3. Abrir el archivo `index.html` en un navegador web.

### Opción 2: clonar con Git

```bash
git clone URL-DEL-REPOSITORIO
cd Tutoria-Facil-UTA
```

Después, abrir:

```text
index.html
```

en un navegador web.

---

## Estructura del proyecto

```text
Tutoria-Facil-UTA/
│
├── index.html
├── README.md
│
├── docs/
│   ├── Informe_Tutoria_Facil_UTA.pdf
│   └── analisis-ihc.md
│
├── evidencias/
│   ├── antes_iteracion.png
│   └── despues_iteracion.png
│
└── evaluacion/
    └── prueba_iteracion.md
```

---

## Trabajo colaborativo

El desarrollo y documentación del proyecto se gestionaron mediante Git y GitHub.

Cada integrante trabajó en una rama independiente asociada a una tarea específica.

| Integrante | Responsabilidad | Rama |
|---|---|---|
| Elizabet | Análisis IHC y requisitos | `feature/analisis-ihc` |
| Andrew | Accesibilidad y usabilidad | `feature/accesibilidad` |
| Sebastian | Mejoras visuales y responsive | `feature/mejoras-visuales` |
| Veronica | Prueba cruzada e iteración | `feature/prueba-iteracion` |

El flujo de colaboración utilizado fue:

```text
Issue
  ↓
Rama individual
  ↓
Cambios
  ↓
Commits
  ↓
Push
  ↓
Pull Request
  ↓
Revisión por otro integrante
  ↓
Aprobación
  ↓
Merge a main
```

Cada integrante realizó cambios relacionados con su responsabilidad y los Pull Requests fueron revisados por otro miembro del equipo antes de integrarse a la rama principal.

---

## Organización de revisiones

Las revisiones de los Pull Requests se distribuyeron entre los integrantes para mantener una revisión cruzada:

| Autor del cambio | Revisor |
|---|---|
| Elizabet | Andrew |
| Andrew | Sebastian |
| Sebastian | Veronica |
| Veronica | Elizabet |

---

## Integrantes

- Elizabet
- Andrew
- Sebastian
- Veronica

---

## Asignatura

**Interacción Humano Computador**

Universidad Técnica de Ambato  
2026

---

## Estado del proyecto

**Prototipo funcional y evaluado.**

Se completaron:

- Diseño del flujo de tutorías.
- Prototipo interactivo.
- Aplicación de principios de IHC.
- Consideraciones de accesibilidad.
- Diseño responsive.
- Prueba cruzada.
- Iteración a partir del comentario del participante.
- Gestión colaborativa mediante Git y GitHub.