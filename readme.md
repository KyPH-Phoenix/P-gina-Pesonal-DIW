Los problemas que he comprobado son los siguientes:

- The page has a logical tab order - OK
- Interactive controls are keyboard focusable - DON'T HAVE
- Interactive elements indicate their purpose and state - DON'T HAVE
- The user's focus is directed to new content added to the page - OK
- User focus is not accidentally trapped in a region - OK
- Custom controls have associated labels - DON'T HAVE
- Custom controls have ARIA roles - DON'T HAVE
- Visual order on the page follows DOM order - OK
- Offscreen content is hidden from assistive technology - DON'T HAVE
- HTML5 landmark elements are used to improve navigation - OK

La mitad ni siquiera son problema porque mi pagina no tiene controles interactivos, ni elementos intevos
y además es una spa. Por lo tanto fuera. Del resto de problemas los he comprobado y estan bien. Las
pestañas tienen orden lògico, se puede navegar solo con teclado y no te quedas pillado en ningun sitio. 
Los links funcionan bien. Uso secciones para estructurar el documento.

Un problema que me ha detectado lighthouse es que tenia h1 y luego h3. Esto es un error de accesibilidad. Es lo único que tengo. Se corrige en un momento.

También había una vulnerabilidad con un follon de librerias que use para probar una cosa y se me olvido
quitarlas.

