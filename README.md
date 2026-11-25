# Trivia Tehuacán

Aplicación web estática hecha con HTML, CSS y JavaScript. No requiere instalación ni servidor. Los récords se guardan en `localStorage` del navegador.

## Ejecutar

Abre `index.html` en un navegador. Para servirla localmente también puedes ejecutar:

```bash
python -m http.server 8000
```

Y visitar `http://localhost:8000`.

## Contenido

- 10 preguntas aleatorias por partida, sin repetir.
- Categorías: Historia, Lugares, Cultura y Naturaleza.
- Dificultad Fácil, Intermedio, Difícil o Mixto.
- 15 segundos por pregunta, puntuación con bonificación por rapidez, rachas y resultados.
- Récord, partidas y aciertos acumulados guardados en `localStorage`.

## Fuentes de referencia del banco inicial

Las preguntas se redactaron a partir de fuentes institucionales. Algunas explicaciones tradicionales del topónimo varían entre documentos, por lo que conviene revisar la redacción antes de publicar una edición definitiva.

- Ayuntamiento de Tehuacán, Manual de organización y procedimientos, antecedentes históricos: https://transparencia.tehuacan.gob.mx/media/files/Transparencia/PRESIDENCIA/catastro.pdf
- Ayuntamiento de Tehuacán, Plan Municipal de Desarrollo: https://transparencia.tehuacan.gob.mx/web/pdf/PLAN%20MUNICIPAL%20DE%20DESARROLLO.pdf
- Auditoría Superior del Estado de Puebla, Informe individual Tehuacán 2023: https://www.auditoriapuebla.gob.mx/images/InformesInd2023/1401_Tehuacan.pdf
- INAH, Zona arqueológica de Tehuacán: https://www.inah.gob.mx/index.php/zonas/tehuacan
- INAH, Valle de Tehuacán-Cuicatlán: https://lugares.inah.gob.mx/es/node/6145
- CONANP, Reserva de la Biosfera Tehuacán-Cuicatlán: https://www.gob.mx/conanp/documentos/reserva-de-la-biosfera-tehuacan-cuicatlan-209465
- Secretaría de Cultura, Sistema de Información Cultural, Museo de Sitio: https://sic.cultura.gob.mx/ficha.php?disciplina=&table=museo&table_id=1901
- Secretaría de Cultura, Sistema de Información Cultural, Museo del Valle: https://sic.cultura.gob.mx/ficha.php?estado_id=21&table=museo&table_id=856
- Secretaría de Cultura, Sistema de Información Cultural, Museo de la Evolución: https://sic.gob.mx/ficha.php?table=museo&table_id=1904

## Nota

El proyecto usa Google Fonts desde CDN (Archivo y JetBrains Mono); si no hay conexión, el navegador usa tipografías de respaldo. La interfaz sigue el lenguaje visual «Consola de Instrumentos» de JuanPancho's (oro sobre grafito) y muestra sus datos de contacto y redes en el pie de página, con un botón flotante de WhatsApp. La aplicación funciona sin backend. Las estadísticas quedan en el navegador y no se sincronizan entre dispositivos.
