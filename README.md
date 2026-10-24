# public

Recursos estáticos que se publican tal cual. Aplica a todo lo que hay por debajo de `public/`.

## Iconos de la PWA
| Archivo | Tamaño | Uso |
|---|---|---|
| `pwa-192x192-v3.png` | 192×192 | Icono estándar del manifest y favicon. |
| `pwa-512x512-v3.png` | 512×512 | Icono estándar del manifest. |
| `pwa-maskable-512x512-v3.png` | 512×512 | Icono `maskable`: el logo debe quedar dentro de la zona segura (círculo central del 80 %). |
| `apple-touch-icon-v3.png` | 180×180 | Icono en iOS al añadir a la pantalla de inicio. |

## Reglas
*   Al cambiar un icono se sube la versión del nombre (`-v2` → `-v3`) para que ninguna caché sirva el anterior.
*   Los nombres deben coincidir con los referenciados en el manifest de `vite.config.ts` y en `index.html`.
*   Aquí no se guardan datos de negocio, ni secretos, ni imágenes de usuarios.
