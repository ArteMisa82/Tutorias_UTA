# Análisis IHC — Tutoría Fácil UTA

## 1. Objetivo

Analizar la interacción entre el estudiante y el sistema Tutoría Fácil UTA,
identificando las necesidades del usuario y las decisiones de diseño
aplicadas en el prototipo.

## 2. Usuario principal

El usuario principal es un estudiante universitario que necesita consultar
la disponibilidad de los docentes, seleccionar un horario y reservar una
tutoría académica de forma rápida y comprensible.

## 3. Necesidades identificadas

El estudiante necesita:

- Consultar horarios disponibles.
- Diferenciar horarios disponibles y ocupados.
- Seleccionar docente, fecha y hora.
- Revisar la información antes de confirmar.
- Recibir una confirmación clara de la reserva.
- Consultar las tutorías registradas.
- Reprogramar una tutoría cuando sea necesario.

## 4. Flujo principal

El flujo principal del prototipo es:

Inicio → Selección → Revisión → Confirmación.

Después de confirmar una tutoría, el estudiante también puede acceder
a "Mis tutorías" y realizar una reprogramación.

## 5. Relación humano-sistema

Durante la interacción:

1. El usuario selecciona un docente.
2. El sistema muestra y actualiza la información seleccionada.
3. El usuario selecciona una fecha.
4. El sistema presenta horarios disponibles y ocupados.
5. El usuario selecciona un horario.
6. El sistema permite continuar a la revisión.
7. El usuario verifica los datos.
8. El sistema solicita la confirmación.
9. El usuario confirma la tutoría.
10. El sistema muestra el estado de reserva confirmada.

Este flujo busca mantener visible el estado del sistema y reducir errores
antes de confirmar una acción.

## 6. Requisitos de usuario

### RU-01 — Consultar disponibilidad
El estudiante debe poder visualizar las fechas y horarios disponibles
para una tutoría.

### RU-02 — Identificar horarios ocupados
El sistema debe diferenciar claramente los horarios disponibles de
aquellos que no pueden seleccionarse.

### RU-03 — Revisar la reserva
El estudiante debe poder revisar el docente, fecha, hora y modalidad
antes de confirmar la tutoría.

### RU-04 — Confirmar la tutoría
El sistema debe proporcionar una confirmación visible después de
registrar correctamente la tutoría.

### RU-05 — Reprogramar
El estudiante debe poder seleccionar un nuevo horario para una tutoría
cuando necesite modificar su cita.

## 7. Criterios de calidad

Para evaluar la experiencia de uso se consideran:

- Efectividad: el usuario debe poder completar la tarea correctamente.
- Eficiencia: el flujo debe requerir pocos pasos y un tiempo reducido.
- Satisfacción: la interfaz debe resultar clara y comprensible.
- Prevención de errores: los horarios ocupados no deben poder seleccionarse.
- Recuperación: el usuario debe poder regresar y corregir información antes
  de confirmar.

## 8. Conclusión

El diseño de Tutoría Fácil UTA prioriza un flujo breve y comprensible.
La información se presenta progresivamente para evitar sobrecargar al
usuario y se permite revisar la información antes de ejecutar la
confirmación final.