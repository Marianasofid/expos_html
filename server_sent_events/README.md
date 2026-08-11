# Server-Sent Events API

## ¿Qué es?

La Server-Sent Events API permite que una página web reciba automáticamente actualizaciones enviadas por un servidor.

A diferencia de una comunicación tradicional en la que la página tiene que solicitar constantemente nueva información, con Server-Sent Events el servidor puede enviar actualizaciones al navegador cuando hay nueva información disponible.

## ¿Para qué sirve?

Puede utilizarse para mostrar información que cambia constantemente, por ejemplo:

- Actualizaciones de noticias.
- Resultados deportivos.
- Cotizaciones.
- Notificaciones.
- Información en tiempo real.

## ¿Cómo funciona?

La página web establece una conexión con el servidor utilizando:

```javascript
new EventSource("demo_sse.php")
```

Cuando el servidor envía información, el evento `onmessage` permite recibirla y mostrarla en la página.

## Importante

Para utilizar un ejemplo real de Server-Sent Events se necesita un servidor que pueda enviar los eventos. Por eso, este ejemplo utiliza PHP como en el tutorial de W3Schools.

## Fuente

https://www.w3schools.com/html/html5_serversentevents.asp