<div align="center">

# 🚌 Integra RZ: School Management Suite
### Sistema Integral de Gestión Escolar, Logística y Finanzas

![Status](https://img.shields.io/badge/Estado-En_Desarrollo-yellow?style=for-the-badge)
![Platform](https://img.shields.io/badge/Plataformas-Windows_|_Android-blue?style=for-the-badge)
![License](https://img.shields.io/badge/Licencia-Propiedad_Intelectual-red?style=for-the-badge)

<br>
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
<img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
<img src="https://img.shields.io/badge/Hive_DB-Local_Storage-orange?style=for-the-badge" />

</div>

---

## 📋 Descripción del Proyecto

**Integra RZ** es una solución de software multiplataforma diseñada para centralizar y optimizar la administración de una institución educativa de nivel básico (Preescolar/Primaria). 

El sistema resuelve la desconexión actual entre las tres áreas críticas de la operación escolar:
1.  **Logística de Transporte Escolar** (Rutas, asistencia y seguridad).
2.  **Gestión Financiera** (Colegiaturas, cafetería y venta de insumos).
3.  **Evaluación Académica y Docente** (Análisis de rendimiento real vs. calificaciones).

El proyecto está diseñado bajo una arquitectura **"Offline-First"** para garantizar operatividad en rutas de transporte sin conexión, sincronizando datos con la nube (Firebase) cuando es posible.

---

## 🚀 Módulos Principales

### 1. 🚌 Módulo Móvil: Logística de Transporte (Android)
Diseñado para la operación en campo bajo condiciones de alta presión y movimiento.
* **UX de Alta Velocidad:** Interfaz basada en **Códigos de Color y Neumorfismo** para identificación rápida de alumnos (sin uso de fotografías por privacidad).
* **Gestión de Seguridad:** Check-in/Check-out de alumnos al subir y bajar de la unidad.
* **Alertas Financieras:** Notificación visual discreta de adeudos al momento de abordar.
* **Tecnología:** Flutter Mobile + Hive (Base de datos local).

### 2. 💻 Módulo de Escritorio: Administración Central (Windows)
El centro de mando para la dirección general.
* **Dashboard Financiero:** Control de ingresos por colegiaturas y micro-transacciones (cafetería/dulces).
* **Evaluación Docente Ponderada:** Algoritmo propio que cruza calificaciones de alumnos con factores de auditoría administrativa y satisfacción de padres, evitando "falsos positivos" en el rendimiento docente.
* **Gestión de Inventarios:** Control simplificado de insumos escolares.

---

## 🛠️ Stack Tecnológico

| Componente | Tecnología | Uso |
| :--- | :--- | :--- |
| **Frontend** | [Flutter](https://flutter.dev/) | Desarrollo de UI nativa para Windows y Android desde un solo código base. |
| **Lenguaje** | [Dart](https://dart.dev/) | Lógica de negocio y tipado fuerte. |
| **Backend / Cloud** | [Firebase](https://firebase.google.com/) | Base de datos NoSQL (Firestore) y Autenticación. |
| **Almacenamiento Local** | **Hive** | Persistencia de datos ultrarrápida para funcionamiento offline en transporte. |
| **Control de Versiones** | Git & GitHub | Gestión del código fuente. |

---

## 📝 Metodología y Análisis de Requerimientos

Este proyecto sigue un enfoque de **Diseño Centrado en el Usuario (UCD)**. 

### Fase 1: Levantamiento de Requerimientos (Completada)
Se realizó una serie de entrevistas formales con la Dirección General (Stakeholder principal) para definir las "Reglas de Negocio".
* **Enfoque de la entrevista:** Usabilidad para usuarios no nativos digitales en entornos de estrés.
* **Hallazgos Clave:**
    * Necesidad crítica de operar sin internet móvil estable.
    * Prioridad de la legibilidad (UI de alto contraste) sobre la estética moderna.
    * Implementación de un sistema de auditoría cualitativa para maestros, no solo cuantitativa.

---

## 🔒 Privacidad y Seguridad

> **Nota Importante:** Este repositorio es un portafolio profesional de desarrollo de software.

* **Datos Sensibles:** No se incluye ningún dato real de alumnos, profesores o estados financieros de la institución. La base de datos utiliza *Mock Data* (Datos ficticios) para demostración.
* **Credenciales:** Las llaves de acceso a Firebase y firmas de la aplicación están protegidas y excluidas del repositorio mediante `.gitignore`.

---

<div align="center">

**Desarrollado por Ernesto Velez Ortega**
</div>
