# Material cursado durante el mes de abril

## Unidad 3: Tipos de ataque

1. `2026.04.06`

   - Cruce de límites de confianza: Ejecución de JavaScript del lado del
     cliente ⇒ XSS (_Cross-Site Scripting_), CSRF (Cross-Site Request
     Forgery)
     - **XSS**: Inyección de _Javascript ejecutable_. Típicamente,
       contenido _a desplegar_ en el cliente Web, no sanitizado. _Vector_:
       Hacer que el cliente interprete contenido provisto por el atacante
       como _inicio de un script_ (p.ej. etiqueta `<script>` o un atributo
       `onerror` de elementos como `<img>`).
     - **CSRF**: Engaña a un cliente (típicamente Web, pero no es
       indispensable) para _realizar una petición cuyo destino controla_ el
       atacante. Normalmente, son peticiones `GET` (no `POST`). CSRF no
       permite mucha interactividad (sólo lanzar solicitudes específicas
       _con la autenticación_ del cliente.
     - _Mitigaciones_:
       - XSS → Codificación de todo el contenido proveniente de fuera del
         sistema _evitando caracteres con significado interpretable_ (`< >
         & # ' "`); [Content Security Policy
         (CSP)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/CSP)
         desde el servidor HTTP
       - CSRF → _tokens_ ocultos que varíen _y sean validados_ por cada
         consulta (no sirve por sesión o por formulario: Por cada
         invocación). Puede enviarse como parámetro o como cookie (o como
         ambos). ¡Ojo! Si hay vulnerabilidad XSS, ésta puede _robar el
         token anti-CSRF_.
     - Espacio para jugar a romper sitios: [XSS
       Game](https://xss-game.appspot.com/). Y... hay que reconocer que no
       siempre es fácil hacerlo, así que si de a tiro no podemos, no está
       prohibido [hacer trampa aprendiendo cómo lo hizo alguien
       más](https://jh123x.com/blog/2022/google-xss-game/).
	   
	   Menos _lúdico_, pero también interesante →
       [XSSTrain](https://xsstrain.com/)
