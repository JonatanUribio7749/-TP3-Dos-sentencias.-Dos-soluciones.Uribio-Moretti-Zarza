# FlexControl · TP3 · Grupo 33

Front End · IFTS 29 · 2026. Entrega indicada en la consigna: 26/11/2026.

## Asignación y origen
Startup: FlexControl. Logística y distribución. Bloque S06-C, Retiro e incidencias.
Objetivo: control de paquetes y coordinación de retiros mediante lectura de etiquetas y avisos al transportista.
Identidad y logo originales: material de estudiantes del IFTS 16, reproducido en la página 45 de la consigna del TP3 del IFTS 29.

R5: «Si la persona responsable confirma el retiro de un paquete listo, el sistema registra la fecha y lo marca como retirado.»

R6: «Si falla el envío del aviso de retiro, el sistema muestra el error y solicita intervención humana, sin marcar el aviso como enviado.»

## Integrantes y aportes
- **Jonatan Emanuel Uribio:** coordinación del encargo al agente, revisión de documentación y solicitud de adaptación del guion a video y gestión de información proporcionada por el resto de los integrantes.
- **Gonzalo Moretti:** revisión lógica de R5 y observaciones de mejora de R6 (plazo de espera y trazabilidad de incidencias), documentadas en su Word.
- **Gabriel Zarza:** Revisión lógica de R6, conclusiones.

La distribución sugerida y el registro de aportes efectivos están en docs/EQUIPO.md. Las asignaciones propuestas no acreditan tareas realizadas. Completar los aportes efectivos y la revisión cruzada antes de entregar.

## Alcance
Landing que explica dos propuestas de flujos agénticos. Incluye sentencias originales, diagramas SVG, detalles desplegables, excepciones, intervención humana y ejemplos interactivos ilustrativos. No realiza envíos ni modifica paquetes. Sin backend, APIs, cuentas ni automatización real.

Se usa HTML semántico, CSS y JavaScript sin dependencias, permitidos por la consigna. Los diagramas se entregan integrados y también como archivos SVG. React no es obligatorio.

## Ejecutar
Opción simple: abrir dist/index.html en un navegador moderno. No requiere Node ni instalaciones.

Con servidor local, desde la raíz:

```sh
python -m http.server 8080 --directory dist
```

Abrir http://localhost:8080. En Windows también puede usarse `py -m http.server 8080 --directory dist` o la extensión Live Server de VS Code sobre dist/index.html.


## Enlaces de entrega
- Repositorio GitHub del grupo: https://github.com/JonatanUribio7749/-TP3-Dos-sentencias.-Dos-soluciones.Uribio-Moretti-Zarza
- Landing pública Vercel: https://dossentencia-dossoluciones.vercel.app

## Construcción agéntica
Aplicación: ChatGPT Work / Codex. Modelo visible para el agente: GPT-6.1; el integrante debe registrar el nombre que efectivamente vea en su aplicación, o «modelo no informado» si no se muestra. No se infiere el modelo a partir del nombre de la aplicación.

Uso: interpretación de consigna, propuesta de contenido, diagramas, generación de HTML/CSS/JS, extracción del logo original, documentación, comprobaciones y correcciones. Los archivos de esta versión se generaron y modificaron por el agente. El grupo debe revisar y comprender lo entregado.

## Proceso de trabajo e iteraciones con el agente

### 1. Interpretación de los requerimientos
Jonatan solicitó analizar la consigna del TP3 y los materiales
D1 a D12, considerando las correcciones anteriores del TP1.
Pidió organizar el trabajo según la rúbrica e identificar
el caso asignado al grupo 33.

Resultado: se identificó FlexControl, bloque S06-C, con las
sentencias R5 y R6, y se delimitó el alcance de la landing.

### 2. Definición de las soluciones
Jonatan pidió preparar las propuestas y sus diagramas antes
de construir la página.

El agente desarrolló entradas, condiciones, acciones,
resultados y alternativas de intervención humana.
Se distinguieron las consecuencias de las sentencias originales
de las decisiones adicionales de diseño.

### 3. Construcción de la landing
Jonatan encargó el desarrollo integral y la documentación
necesaria para revisar y presentar el proyecto.

El agente generó HTML, CSS y JavaScript, incorporó el logo
original y construyó los diagramas, desplegables y ejemplos
interactivos ilustrativos.

### 4. Correcciones de claridad
Durante la revisión, el agente detectó que el nodo de fallo
de R6 debía expresar explícitamente que el aviso no quedaba
marcado como enviado.

Se ajustó a:
«Error · no enviado · revisión humana».

También se sustituyó una flecha del botón principal que no
se representaba correctamente.

### 5. Adaptación de la presentación
Jonatan solicitó transformar el guion inicial de coloquio
en un guion para video grabado, sin preguntas.

Pidió precisar qué dice cada integrante y qué debe mostrar
él en pantalla durante cada intervención.

Resultado: guion secuencial con apertura, explicación de R5,
explicación de R6 y cierre, acompañado por acciones de pantalla.

### 6. Revisión aportada por Gonzalo
Gonzalo documentó su revisión de los casos de R5 y señaló
dos aspectos para precisar en R6:

- El criterio temporal para pasar de pendiente a incierto.
- La vinculación entre la incidencia del aviso y el paquete.

Jonatan compartió ese documento y pidió revisar los archivos
del proyecto para incorporar sus observaciones.

### 7. Incorporación de las observaciones
El agente añadió un plazo configurable como decisión de diseño:
dentro del plazo, el aviso permanece pendiente; vencido el plazo
sin resultado concluyente, se considera incierto.

También explicitó la relación incidencia-aviso-paquete,
añadió el ejemplo «Dentro del plazo» y actualizó diagramas,
textos, ejemplos y documentación.

### 8. Comprobación y cierre
En la versión revisada, el agente comprobó sintaxis JavaScript,
anclas internas, identificadores únicos, renderizado de los
siete ejemplos mediante DOM simulado y generación reproducible.

La revisión visual personal de esta versión, la comprobación
de los enlaces públicos y la participación efectiva de Gabriel
deben registrarse cuando se realicen.


