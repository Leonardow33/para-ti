# Para ti 💌

Página para invitar a salir a alguien, con un flujo de 5 pantallas:

1. **Sobre** animado: se abre al tocarlo.
2. **Carta** escrita a mano que aparece línea por línea.
3. **La pregunta**: el botón "No" escapa, cambia de texto y el "Sí" se hace más grande. El gatito se pone triste si ella intenta decir que no.
4. **Elegir la cita**: plan, día y hora.
5. **Boleto para dos** con un botón para confirmar por WhatsApp.

## Personalizar el link (sin tocar código)

```
https://leonardow33.github.io/para-ti/?para=NOMBRE&de=TU_NOMBRE&tel=51999999999
```

- `para`: nombre de ella
- `de`: tu nombre (o la firma de la carta)
- `tel`: tu WhatsApp con código de país, sin `+` ni espacios

## Personalizar el contenido

Edita el objeto `CONFIG` al inicio del `<script>` en `index.html`: el texto de la carta, los planes, los días, las horas y los mensajes del botón "No".

Referencias: [hallowshaw/will-you-go-out-with-me](https://github.com/hallowshaw/Will-you-go-out-with-me) y [subhajeetch/forced-confession](https://github.com/subhajeetch/Forced-Confession), dos páginas con el clásico botón "No" que se escapa.
