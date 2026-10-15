# Mi portafolio

Este es el código de mi página personal. Soy Mario Gaytán, estudio Ingeniería Cibernética y Sistemas Computacionales en la Universidad Marista de Guadalajara y hago páginas web y sistemas para negocios.

La armé para tener en un solo lugar lo que he hecho y para poder enseñarle ejemplos a la gente que me pide una página.

## Qué hay aquí

- `index.html` es la página principal: quién soy, qué servicios doy, mis proyectos y cómo contactarme.
- `img/raices/` tiene las capturas de Raíces, una app que hice para armar árboles genealógicos.
- `demos/` tiene cuatro páginas de ejemplo para negocios locales:
  - **Cafetería**: el cliente arma su pedido desde el menú y lo manda por WhatsApp para pasar a recogerlo.
  - **Taquería**: pedidos a domicilio, con costo de envío según la colonia y pedido mínimo.
  - **Papelería**: un cotizador de impresiones que da el precio al momento, catálogo con buscador y envío de listas escolares.
  - **Barbería**: agenda de citas donde escoges servicio, barbero, día y hora libre.

Los negocios de las demos no existen. Los nombres, precios, reseñas y teléfonos son inventados, y los mapas apuntan a lugares públicos (parques y plazas) para no usar la dirección de nadie. Si alguna vez coincide un nombre con un negocio real, es casualidad.

## Cómo está hecho

Quise que fuera lo más simple posible de subir y de mantener, así que no usa frameworks ni paso de compilación. Es HTML, CSS y JavaScript normal, cada página en un solo archivo.

- Los íconos son de [Lucide](https://lucide.dev) y se cargan desde unpkg. No uso emojis en la interfaz porque no se ven igual en todos los celulares.
- Las fuentes vienen de Google Fonts.
- Los pedidos y las citas no pasan por ningún servidor: la página arma el mensaje y abre WhatsApp con el texto listo.
- Todo está pensado primero para celular, porque es donde la gente lo va a abrir.

## Verlo en tu computadora

Puedes abrir `index.html` con doble clic, pero algunas cosas (como las vistas previas de las demos) funcionan mejor con un servidor local. Si tienes Python:

```bash
python -m http.server 8765
```

y luego entra a http://localhost:8765.

## Adaptar una demo a un negocio real

Al inicio del `<script>` de cada demo hay un bloque marcado como configuración del negocio. Ahí se cambian el número de WhatsApp, el horario, el menú o los productos y los precios. Lo demás se queda igual, solo hay que poner las fotos del lugar donde dice que van.

## Contacto

Si te interesa una página así para tu negocio o tienes otro proyecto, escríbeme a mario.arturo.go@gmail.com o búscame en GitHub como [MarioGaytan](https://github.com/MarioGaytan).
