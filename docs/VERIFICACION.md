# Verificación · 13/11/2026

## Comprobado por el agente
- Sintaxis de JavaScript: node --check dist/app.js, sin errores.
- Apertura del sitio en navegador de escritorio: correcta.
- Logo original completo: inspección visual correcta.
- Diagramas SVG visibles: inspección en navegador.
- Retiro repetido: al seleccionar el ejemplo se muestra conservación del registro original y revisión humana.
- Resultado incierto: se muestra que no hay confirmación de éxito ni fallo concluyente y se pide revisión.
- Desplegable Datos de entrada de R6: abre con clic y cierra con Enter.
- Navegación Incidencias: dirige a #aviso.
- Revisión lógica: ambos diagramas diferencian condición cumplida y alternativa. Los supuestos se declaran en desplegables.
- Mejora posterior a la inspección: se añade «no enviado» al nodo de fallo R6.

## Casos de aceptación lógica
| Regla | Entrada | Resultado |
|---|---|---|
| R5 | Listo + confirma responsable | Fecha y estado retirado |
| R5 | Sin confirmación | Mantener estado y revisión (propuesta) |
| R5 | Ya retirado | Conservar registro y revisión (caso límite propuesto) |
| R6 | Fallo confirmado | Error, intervención humana y no enviado |
| R6 | Éxito confirmado | Registrar envío (propuesta) |
| R6 | Resultado incierto | No afirmar éxito y revisión (caso límite propuesto) |

## Pendiente del grupo
- Recorrer personalmente todos los casos y explicar ambas soluciones.
- Registrar aportes y una mejora real surgida de la revisión cruzada.
- Publicar repositorio y landing en las cuentas del grupo.
- Completar enlaces en README y comprobar ambos desde ventana sin sesión.

No se declara una cobertura automatizada ni una prueba pública sin sesión que no se haya realizado.
