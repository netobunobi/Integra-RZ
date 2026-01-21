# 📋 Guía de Levantamiento de Requerimientos
**Proyecto:** Integra RZ – Sistema de Gestión Escolar
**Fecha:** Enero 2026
**Entrevistado:** Dirección General
**Objetivo:** Definir reglas de negocio, flujos de trabajo críticos y oportunidades de optimización futura.

---

## 🚍 BLOQUE A: Logística y Transporte (Misión Crítica / Móvil)
*Objetivo: Entender la operación en campo para diseñar la interfaz Android.*

1.  **El entorno físico:**
    "Durante el recorrido, ¿usted lleva el celular en la mano todo el tiempo, o lo guarda en la bolsa/soporte entre parada y parada? Si lo guarda, ¿se bloquea la pantalla?"
    *(Nota: Define si se requiere modo 'Always On' o desbloqueo rápido).*

2.  **Conectividad y Señal:**
    "¿Hay zonas en la ruta donde se vaya la señal de internet por completo? Si es así, ¿por cuánto tiempo suele durar esa desconexión?"

3.  **Protocolo de Emergencia (Niño No Entregado):**
    "Si llega a la casa de un niño para entregarlo y no hay nadie para recibirlo, ¿qué hace exactamente? ¿Se lo lleva de regreso a la escuela? ¿Espera un tiempo determinado? ¿A quién llama primero?"

4.  **Identificación Visual Rápida:**
    "Dado que necesitamos identificar a los niños en segundos y sin usar fotografías (por privacidad). ¿Le resultaría útil que asignemos un **Color Fijo** a cada grado? (Ej: 1º Amarillo, 2º Azul). ¿O prefiere otro método visual?"

---

## 💰 BLOQUE B: Finanzas y Cafetería (Administración)
*Objetivo: Estructurar la Base de Datos y las reglas de crédito.*

5.  **Flexibilidad de Pagos:**
    "Cuando un padre paga, ¿siempre cubre el total exacto? ¿O sucede que le dan 'abonos' parciales? ¿Necesita que el sistema calcule automáticamente el saldo restante?"

6.  **Reglas de la Cafetería (Crédito):**
    "Si un alumno tiene deuda de colegiatura, ¿el sistema debe permitirle comprar en la tiendita/cafetería, o debe mostrar una alerta de 'Cobrar Deuda' al intentar venderle?"

7.  **Nivel de Detalle en Reportes:**
    "Al final del día, ¿qué prefiere ver en su corte de caja?
    * Opción A: Detallado ('3 jugos, 2 tortas').
    * Opción B: Solo montos ('Venta Cafetería: $500.00')."

8.  **Comprobantes:**
    "Cuando recibe un pago, ¿necesita generar un recibo físico/digital en ese momento, o solo lo registra en su control personal?"

---

## 🎓 BLOQUE C: Evaluación de Maestros (Lógica de Negocio)
*Objetivo: Calibrar el algoritmo para evitar 'falsos positivos'.*

9.  **El Factor 'Realidad':**
    "Un grupo con calificaciones de 10 no siempre indica un buen maestro. ¿Le gustaría tener una opción para calificar usted misma la 'honestidad' del maestro? (Ej: Un control para indicar si el maestro es estricto o 'barco')."

10. **Peso de las Incidencias:**
    "Para restar puntos a un maestro en el ranking, ordene qué considera más grave (de mayor a menor):
    * Llegadas tarde.
    * Entrega tardía de planeaciones.
    * Quejas de los padres de familia."

11. **Visualización:**
    "¿Cómo prefiere ver el 'Top de Maestros'? ¿Una lista simple (1, 2, 3) o una gráfica que muestre si mejoraron o empeoraron respecto al mes anterior?"

---

## 🖥️ BLOQUE D: Experiencia de Usuario (UX)
*Objetivo: Adaptar el sistema a las preferencias del usuario.*

12. **Método de Entrada:**
    "Al usar la computadora, ¿prefiere escribir los datos con el teclado, o prefiere seleccionar opciones de listas con el ratón (clics) para escribir lo menos posible?"

13. **Terminología:**
    "¿Qué palabras usa usted exactamente? ¿'Mensualidad' o 'Colegiatura'? ¿'Recreo' o 'Receso'? Queremos que el sistema hable su mismo idioma."

---

## 📄 BLOQUE E: Trámites y Documentación (Alcance Administrativo)
*Objetivo: Identificar tareas repetitivas automatizables.*

14. **El 'Dolor de Cabeza' Documental:**
    "De todos los papeles que llena o imprime (listas, boletas, cartas), ¿cuál es el que más tiempo le quita o le resulta más tedioso?"

15. **Inscripciones:**
    "¿Le gustaría poder llenar la ficha de inscripción de un alumno nuevo directamente en el sistema mientras entrevista a los padres, eliminando el papel inicial?"

16. **Listas de Asistencia:**
    "¿Le gustaría que el sistema pudiera imprimir las listas de asistencia ya con los nombres cargados para los maestros, o prefiere seguir usando el método manual actual?"

---

## 🚀 BLOQUE F: Futuro y Optimización (Scalability)
*Objetivo: Visualizar la Fase 2 del proyecto.*

17. **Comunicación Automática:**
    "En un mundo ideal, ¿le gustaría que el sistema enviara recordatorios de pago automáticos (WhatsApp/Correo) a los padres deudores, o prefiere mantener ese trato 100% personal?"

18. **Credencialización (Códigos QR):**
    "Para el futuro, ¿cree viable que los alumnos usen una credencial con código para escanearlos al subir al transporte (agilizando el pase de lista), o lo ve poco práctico?"

19. **La Varita Mágica:**
    "Si pudiera resolver 'mágicamente' un solo problema extra de la escuela con este sistema (que no sea dinero ni transporte), ¿cuál sería?"

---

**🏁 Cierre:**
*Muchas gracias por la información. Con esto desarrollaré un prototipo visual para revisarlo juntos antes de iniciar la programación definitiva.*