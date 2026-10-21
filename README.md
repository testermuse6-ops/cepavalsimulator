# Simulador Chatbot CEPAVAL

Chat en vivo que replica el flujo ramificado del chatbot de CEPAVAL, para simular y revisar su actividad antes de usarlo con pacientes reales.

## Cómo usarlo

Abre `index.html` en cualquier navegador (no necesita servidor ni instalación). Escribe **«hola»** para ver el menú principal:

1. Agendar cita
2. Servicios
3. Precios
4. Ubicación y horarios
5. Ya soy paciente
6. Hablar con una persona

Incluye validaciones del flujo de cita (edad en números, fecha futura confirmada, período y hora disponible → estado `PENDING`; cancelación → `CANCELLED`), derivaciones a recepción, emergencias y no-diagnóstico, y un panel de revisión con el estado en vivo de la simulación.

## Datos ficticios

Todos los pacientes y citas de ejemplo son ficticios (por ejemplo, Sofía Herrera, Diego Ramos y María Torres). Ningún dato es real.

Las direcciones de las sedes se muestran en texto genérico porque el documento de flujo original no incluye direcciones exactas.
