# public

Recursos estáticos que se publican tal cual. Aplica a todo lo que hay por debajo de `public/`.

## Iconos de la PWA
| Archivo | Tamaño | Uso |
|---|---|---|
| `pwa-192x192.png` | 192×192 | Icono estándar del manifest. |
| `pwa-512x512.png` | 512×512 | Icono estándar del manifest. |
| `pwa-maskable-512x512.png` | 512×512 | Icono `maskable`: el logo debe quedar dentro de la zona segura (círculo central del 80 %). |
| `apple-touch-icon.png` | 180×180 | Icono en iOS al añadir a la pantalla de inicio. |
| `flowserve-mark.svg` | vectorial | Favicon y origen del que se generan los PNG. |

## Reglas
*   Los PNG se generan a partir de `flowserve-mark.svg`; no se editan a mano.
*   Los nombres deben coincidir con los referenciados en el manifest de `vite.config.ts` y en `index.html`.
*   Aquí no se guardan datos de negocio, ni secretos, ni imágenes de usuarios.
