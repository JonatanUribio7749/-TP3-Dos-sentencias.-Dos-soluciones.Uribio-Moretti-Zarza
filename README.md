# FlexControl · TP3 · Grupo 33

Front End · IFTS 29 · 2026. Entrega indicada en la consigna: 26/11/2026.

## Asignación y origen
Startup: FlexControl. Logística y distribución. Bloque S06-C, Retiro e incidencias.
Objetivo: control de paquetes y coordinación de retiros mediante lectura de etiquetas y avisos al transportista.
Identidad y logo originales: material de estudiantes del IFTS 16, reproducido en la página 45 de la consigna del TP3 del IFTS 29.

R5: «Si la persona responsable confirma el retiro de un paquete listo, el sistema registra la fecha y lo marca como retirado.»

R6: «Si falla el envío del aviso de retiro, el sistema muestra el error y solicita intervención humana, sin marcar el aviso como enviado.»

## Integrantes y aportes
- Jonatan Emanuel Uribio.
- Gonzalo Moretti.
- Gabriel Zarza.

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

## Publicar en Vercel
1. Crear un repositorio propio en GitHub y subir el contenido descomprimido de este proyecto.
2. Importar ese repositorio en Vercel.
3. Framework Preset: Other. Root Directory: raíz del proyecto. Sin comando de build. Output Directory: dist.
4. Publicar y abrir la URL asignada desde una ventana sin sesión.
5. Completar los dos enlaces de entrega abajo y verificar que el repositorio de GitHub sea accesible sin sesión.

vercel.json incluye la configuración estática. No compartir el enlace privado de revisión como si fuera la entrega pública.

## Enlaces de entrega
- Repositorio GitHub del grupo: PENDIENTE DE PUBLICAR EN LA CUENTA DEL GRUPO.
- Landing pública Vercel: PENDIENTE DE PUBLICAR EN LA CUENTA DEL GRUPO.

## Construcción agéntica
Aplicación: ChatGPT Work / Codex. Modelo visible para el agente: GPT-6.1; el integrante debe registrar el nombre que efectivamente vea en su aplicación, o «modelo no informado» si no se muestra. No se infiere el modelo a partir del nombre de la aplicación.

Uso: interpretación de consigna, propuesta de contenido, diagramas, generación de HTML/CSS/JS, extracción del logo original, documentación, comprobaciones y correcciones. Los archivos de esta versión se generaron y modificaron por el agente. El grupo debe revisar y comprender lo entregado.

## Evidencia real de iteración
- Encargo del usuario: «necesito que te encargues de este trabajo de forma integra [...] dejando todo listo para que yo lo presente».
- Primera implementación: dos flujos SVG, detalles nativos, ejemplos seleccionables, identidad original y navegación por secciones.
- Problema detectado por el agente en revisión: el nodo del fallo R6 no expresaba explícitamente la prohibición de marcar el aviso como enviado.
- Corrección realizada por el agente: cambiar el nodo a «Error · no enviado · revisión humana».
- Motivo: hacer visible la consecuencia completa de R6 dentro del propio diagrama.
- Mejora de presentación: sustituir una flecha que no se representaba correctamente en el botón principal.

Esto evidencia iteración del agente. No sustituye la revisión entre compañeros exigida para el nivel Propone del criterio de participación.

## Verificación
Consultar docs/VERIFICACION.md: diferencia pruebas realizadas por el agente de verificaciones pendientes del grupo y de publicación.

## Archivos
- dist/: sitio listo para servir o publicar.
- docs/GUIA_PRESENTACION.md: recorrido y preguntas para la defensa.
- docs/EQUIPO.md: propuesta de responsabilidades y registro real a completar.
- docs/RUBRICA.md: matriz de criterios y evidencia.
- docs/VERIFICACION.md: revisión técnica y lógica.
- docs/R5.svg y R6.svg: diagramas exportados.
- generate.py: fuente de generación del sitio, no necesaria para abrirlo.
