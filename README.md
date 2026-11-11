# DESPIDO O ASCENSO
## El pollito ejecutivo

Juego de decisiones con humor de oficina dominicano, creado para Juan E Peralta. Eres el Pollito Ejecutivo en Santo Domingo: sobrevive 30 días sin quedarte sin plata, sin reputación ni sin nervios.

### Cómo jugar
- Abre `index.html` en un navegador, sin instalar nada. En la primera partida se muestra el tutorial; también puedes abrir **¿CÓMO SE JUEGA?** desde la portada.
- Desliza o arrastra cada tarjeta a izquierda/derecha, toca una opción o usa las flechas del teclado.
- PLATA, ESTRÉS y REPUTACIÓN empiezan en 50. Pierdes si ESTRÉS llega a 100, o si PLATA o REPUTACIÓN llegan a 0.
- Hay 20 dilemas en orden aleatorio; el mazo se vuelve a mezclar cuando se agota. El Gallo Gerente evalúa en los días 10, 20 y 30; esas tarjetas cuentan como días.
- Tras la evaluación del día 30, REPUTACIÓN >= 80 y PLATA >= 70 permiten elegir entre CEO y abrir un colmado. En otro caso: Ascenso a Gerente.

### Los seis finales
Colapso nervioso · Despedido: ni pa'l motoconcho · Despedido por el gerente · Ascenso a Gerente · CEO sin alma · El Colmado de la Esquina (final bueno secreto).

Las insignias y el tutorial visto se guardan con localStorage en cada navegador. Borrar esos datos reinicia el registro.

### Tecnología
HTML/CSS/JS puro en un único `index.html`, arte SVG original, sin dependencias externas, sin compilación y sin sonido. Diseño vertical adaptable para móvil y marco centrado en escritorio. Compartir es opcional y solo aparece en los finales.

### GitHub Pages
Publicación desde la rama `main`, carpeta raíz `/`. No se necesita archivo de workflow.
