# Guía de presentación · 4 a 5 minutos

Distribución sugerida: cada integrante debe adaptar el guion, recorrer la página y entender los dos flujos antes de exponer.

## Apertura · Jonatan · 45 segundos
«Somos el grupo 33. Nos tocó FlexControl, una startup de logística creada por estudiantes del IFTS 16. Trabajamos el bloque Retiro e incidencias, con las reglas R5 y R6. Diseñamos dos propuestas de agentes y las explicamos en una landing construida mediante instrucciones a un agente de programación.»

Mostrar presentación, logo original y navegación.

## R5 · Gonzalo · 1 minuto
«La primera regla indica que, cuando la persona responsable confirma el retiro de un paquete listo, se registra la fecha y se lo marca como retirado. El futuro agente consultaría el paquete y su estado. Las dos condiciones deben cumplirse. Si falta confirmación, nuestra propuesta es conservar el estado y pedir revisión. Si ya está retirado, conservamos la fecha original para evitar duplicados. Estas dos alternativas son decisiones de diseño añadidas, no consecuencias obligatorias de la sentencia.»

Mostrar diagrama y seleccionar Retiro válido y Retiro repetido. Abrir Qué exige la sentencia y Decisiones añadidas por el grupo.

## R6 · Gabriel · 1 minuto
«La segunda regla trata un fallo en el aviso. El agente mostraría el error, pediría intervención humana y no lo marcaría como enviado. Agregamos un caso límite: si el resultado es incierto, tampoco afirmamos éxito. Solo proponemos registrar un envío exitoso cuando hay una confirmación explícita.»

Mostrar diagrama y seleccionar Fallo confirmado y Resultado incierto. Abrir Excepción e intervención humana.

## Criterio y cierre · Jonatan · 45 segundos
«Retirado y enviado son estados diferentes: uno corresponde al paquete y otro al aviso. El fallo del aviso no revierte por sí solo un retiro registrado. La landing explica los procesos, pero no envía mensajes ni realiza automatizaciones reales. Usamos HTML, CSS, JavaScript y diagramas SVG. Los desplegables funcionan con clic y teclado.»

Mostrar sección Criterio. Presentar repositorio y README con los enlaces definitivos una vez publicados.

## Preguntas que deben poder contestar
- ¿Dónde está el agente? Se propone como un futuro responsable de consultar información y decidir acciones; la landing no lo ejecuta.
- ¿Por qué no usamos React? Es opcional. Una landing sin dependencias cubre el alcance y se publica fácilmente.
- ¿Qué comprueba R5? Que exista confirmación de la persona responsable sobre un paquete listo.
- ¿Qué pasa si no se cumple? La sentencia no fija la alternativa; proponemos revisión humana.
- ¿Qué hace R6? Mostrar el error, pedir ayuda humana y no marcar el aviso como enviado.
- ¿Por qué distinguimos incertidumbre? No recibir un error no demuestra éxito.
- ¿Qué agregó el equipo? Consultas propuestas, comprobación de duplicados, tratamiento de incertidumbre y derivaciones fuera de lo definido por las reglas.
- ¿Cómo se construyó? Mediante instrucciones al agente, generación de archivos y correcciones. Mostrar ejemplos reales del README.
- ¿Cómo colaboraron? Explicar únicamente tareas realmente realizadas y registradas en EQUIPO.md.
- ¿Qué falta para producción? Implementar almacenamiento, identidad, permisos, integración de avisos y manejo transaccional. Eso está fuera del TP.

## Antes de presentar
Abrir la landing definitiva en desktop. Probar ambos flujos. Revisar que los desplegables abran y cierren con teclado. Confirmar aportes y una mejora colaborativa real. Comprobar repositorio y sitio público sin iniciar sesión.
