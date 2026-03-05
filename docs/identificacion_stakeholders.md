# Identificación de Stakeholders
**Proyecto:** Sistema de Gestión de Citas con Especialistas  
**Issue:** #4  
**Sprint:** Inicio y Planificación  
**Fecha:** 05/03/2026  

---

## 1. Introducción

Este documento identifica todas las personas y grupos involucrados en el sistema de gestión de citas hospitalarias, analizando su nivel de influencia e interés en el proyecto.

---

## 2. Tabla de Stakeholders

| ID | Stakeholder | Rol en el sistema | Interés | Influencia | Prioridad |
|----|-------------|-------------------|---------|------------|-----------|
| SK-01 | Pacientes | Usuarios finales que solicitan y gestionan sus citas | Alto | Bajo | Alta |
| SK-02 | Médicos especialistas | Reciben y gestionan las citas asignadas | Alto | Medio | Alta |
| SK-03 | Personal administrativo | Gestiona el sistema de citas a diario | Alto | Alto | Alta |
| SK-04 | Equipo de TI del hospital | Mantiene y da soporte técnico al sistema | Medio | Alto | Alta |
| SK-05 | Dirección del hospital | Toma decisiones estratégicas y aprueba el proyecto | Bajo | Alto | Media |
| SK-06 | Equipo de desarrollo | Diseña e implementa el sistema | Alto | Alto | Alta |

---

## 3. Descripción detallada

### SK-01 · Pacientes
- **Descripción:** Personas que necesitan pedir cita con un especialista del hospital.
- **Necesidades:** Proceso sencillo, rápido y accesible para solicitar, modificar o cancelar citas.
- **Expectativas:** Confirmación de cita, recordatorios y tiempos de espera reducidos.
- **Posibles conflictos:** Dificultad de uso si no tienen acceso o habilidades digitales.

### SK-02 · Médicos especialistas
- **Descripción:** Profesionales médicos que atienden a los pacientes según las citas asignadas.
- **Necesidades:** Visualizar su agenda de forma clara, recibir información del paciente previamente.
- **Expectativas:** Sistema que no interrumpa su flujo de trabajo clínico.
- **Posibles conflictos:** Resistencia al cambio si el sistema actual les resulta más cómodo.

### SK-03 · Personal administrativo
- **Descripción:** Empleados que gestionan el sistema de citas diariamente (llamadas, asignaciones, cancelaciones).
- **Necesidades:** Herramienta eficiente que reduzca la carga de trabajo manual.
- **Expectativas:** Interfaz intuitiva, gestión de incidencias y reportes automáticos.
- **Posibles conflictos:** Necesidad de formación para adaptarse al nuevo sistema.

### SK-04 · Equipo de TI del hospital
- **Descripción:** Responsables de la infraestructura tecnológica y soporte del hospital.
- **Necesidades:** Sistema seguro, escalable e integrable con los sistemas existentes del hospital.
- **Expectativas:** Documentación técnica completa y mantenimiento sencillo.
- **Posibles conflictos:** Incompatibilidades con sistemas legacy del hospital.

### SK-05 · Dirección del hospital
- **Descripción:** Órgano de gobierno que aprueba presupuestos y decisiones estratégicas.
- **Necesidades:** Reducción de costes operativos y mejora de la satisfacción del paciente.
- **Expectativas:** Retorno de inversión claro y cumplimiento normativo.
- **Posibles conflictos:** Restricciones presupuestarias.

### SK-06 · Equipo de desarrollo
- **Descripción:** Equipo encargado de diseñar, desarrollar y validar el sistema.
- **Necesidades:** Requisitos claros, feedback continuo de los usuarios y acceso a los sistemas del hospital.
- **Expectativas:** Colaboración fluida con el resto de stakeholders.
- **Posibles conflictos:** Cambios de requisitos a mitad del desarrollo.

---

## 4. Matriz de Poder / Interés

```
INFLUENCIA
  Alta |  [SK-05 Dirección]  |  [SK-03 Administ.] [SK-04 TI] [SK-06 Dev]  |
       |---------------------|----------------------------------------------|
  Baja |                     |  [SK-01 Pacientes] [SK-02 Médicos]           |
       |_____________________|______________________________________________|
                  Bajo interés                        Alto interés
```

| Cuadrante | Stakeholders | Estrategia |
|-----------|-------------|------------|
| Alto interés + Alta influencia | SK-03, SK-04, SK-06 | Gestionar de cerca |
| Alto interés + Baja influencia | SK-01, SK-02 | Mantener informados |
| Bajo interés + Alta influencia | SK-05 | Mantener satisfechos |

---

## 5. Conclusiones

Los stakeholders más críticos para el éxito del proyecto son el **personal administrativo** (usuarios principales del sistema), los **pacientes** (beneficiarios finales) y el **equipo de TI** (soporte técnico). Se recomienda involucrarlos activamente en la validación de requisitos y pruebas del sistema.
