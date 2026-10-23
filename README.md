# Tests Caminos GVA

Tests de la parte específica de la oposición A1-04-03 (Ingeniería de Caminos, Canales y Puertos, Generalitat Valenciana).

- `index.html`: la página de tests (menú, una pregunta por pantalla, saltar, corrección al momento, puntuación, repaso y repetir fallos). El progreso se guarda en el navegador; usa «Exportar progreso» para tener copia o pasarlo a otro dispositivo.
- `validar.html`: comprueba un test nuevo antes de subirlo y reparte de forma equilibrada las letras correctas.
- `tests/`: un archivo JSON por test. La página los muestra solos en el menú.
- `INSTRUCCIONES_GEM.md`: instrucciones del Gem de Gemini que genera los tests.

## Añadir un test nuevo

1. En Gemini, abre el Gem «Tests Caminos», adjunta los temas y las normas y pide el test indicando su número (p. ej. «test04 con los temas 46 y 47»).
2. Copia el bloque JSON que te devuelva y pégalo en `validar.html` (desde la propia web: enlace al final del menú).
3. Pulsa «Validar». Si avisa de letras desequilibradas, pulsa «Equilibrar letras». Revisa a mano las cifras y artículos dudosos.
4. Pulsa «Descargar archivo».
5. En GitHub: carpeta `tests` → «Add file» → «Upload files» → arrastra el archivo → «Commit changes».
6. En uno o dos minutos aparece en la página.
