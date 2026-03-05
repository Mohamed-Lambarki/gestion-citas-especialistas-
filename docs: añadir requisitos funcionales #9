# Requisitos Funcionales
**Proyecto:** Sistema de Gestión de Citas con Especialistas  
**Issue:** #9  
**Sprint:** Identificación de requisitos  
**Fecha:** 05/03/2026  

---

## 1. Introducción

Este documento recoge los requisitos funcionales del sistema de gestión de citas con especialistas del hospital, identificados a partir del análisis de los procesos actuales y las entrevistas con los stakeholders.

---

## 2. Requisitos funcionales

### RF-01 · Solicitud de cita
- **Descripción:** El paciente debe poder solicitar una cita con un médico especialista a través de la aplicación.
- **Actor:** Paciente
- **Prioridad:** Alta
- **Criterios de aceptación:**
  - El paciente puede seleccionar especialidad y médico disponible.
  - El sistema muestra los horarios disponibles en tiempo real.
  - El paciente recibe confirmación inmediata de la cita.

---

### RF-02 · Cancelación y modificación de cita
- **Descripción:** El paciente o el administrativo debe poder cancelar o modificar una cita existente.
- **Actor:** Paciente / Administrativo
- **Prioridad:** Alta
- **Criterios de aceptación:**
  - Se puede cancelar una cita con al menos 24h de antelación.
  - Al cancelar, el hueco queda disponible para otros pacientes.
  - El paciente recibe notificación de la cancelación o modificación.

---

### RF-03 · Recordatorios automáticos
- **Descripción:** El sistema debe enviar recordatorios automáticos de cita a los pacientes.
- **Actor:** Sistema
- **Prioridad:** Alta
- **Criterios de aceptación:**
  - Se envía recordatorio 48h antes de la cita por SMS o email.
  - Se envía un segundo recordatorio 2h antes de la cita.
  - El paciente puede confirmar o cancelar desde el recordatorio.

---

### RF-04 · Gestión de agenda del especialista
- **Descripción:** El administrativo debe poder gestionar la agenda de cada médico especialista.
- **Actor:** Administrativo
- **Prioridad:** Alta
- **Criterios de aceptación:**
  - Se puede bloquear o liberar franjas horarias en la agenda.
  - Se pueden asignar citas manualmente a un especialista.
  - La agenda es visible en formato semanal y mensual.

---

### RF-05 · Consulta de agenda por el médico
- **Descripción:** El médico especialista debe poder consultar su agenda de citas del día y de la semana.
- **Actor:** Médico especialista
- **Prioridad:** Alta
- **Criterios de aceptación:**
  - El médico puede ver nombre, motivo y datos básicos del paciente.
  - La agenda se actualiza en tiempo real.
  - Se puede acceder desde dispositivo móvil y escritorio.

---

### RF-06 · Reasignación automática de huecos
- **Descripción:** Cuando se cancela una cita, el sistema debe ofrecer el hueco automáticamente a pacientes en lista de espera.
- **Actor:** Sistema
- **Prioridad:** Media
- **Criterios de aceptación:**
  - El sistema notifica al primer paciente en lista de espera.
  - Si no confirma en 2h, se ofrece al siguiente.
  - El proceso es completamente automático.

---

### RF-07 · Historial de citas del paciente
- **Descripción:** El paciente debe poder consultar el historial completo de sus citas anteriores y futuras.
- **Actor:** Paciente
- **Prioridad:** Media
- **Criterios de aceptación:**
  - Se muestran citas pasadas y futuras con fecha, médico y estado.
  - Se puede descargar el resumen de citas en PDF.
  - El historial es accesible desde la app móvil y la web.

---

### RF-08 · Generación de informes
- **Descripción:** El sistema debe permitir generar informes de ocupación, cancelaciones y estadísticas de uso.
- **Actor:** Administrativo / Dirección
- **Prioridad:** Baja
- **Criterios de aceptación:**
  - Se pueden filtrar informes por especialidad, médico y periodo.
  - Los informes se pueden exportar en formato CSV y PDF.
  - Los datos se actualizan diariamente.

---

### RF-09 · Autenticación y control de acceso
- **Descripción:** El sistema debe autenticar a los usuarios y controlar el acceso según su rol.
- **Actor:** Paciente / Médico / Administrativo
- **Prioridad:** Alta
- **Criterios de aceptación:**
  - Cada usuario accede solo a las funciones de su rol.
  - El sistema soporta autenticación con usuario/contraseña.
  - Se bloquea la cuenta tras 5 intentos fallidos.

---

## 3. Resumen de prioridades

| Prioridad | Requisitos |
|-----------|-----------|
| Alta | RF-01, RF-02, RF-03, RF-04, RF-05, RF-09 |
| Media | RF-06, RF-07 |
| Baja | RF-08 |

---

## 4. Conclusiones

Se han identificado 9 requisitos funcionales que cubren los principales flujos del sistema. Los requisitos de alta prioridad deben ser implementados en el Sprint 2, mientras que los de media y baja prioridad se abordarán en sprints posteriores.
