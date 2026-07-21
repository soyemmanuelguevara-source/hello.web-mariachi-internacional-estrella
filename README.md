# Brief de Proyecto — Mariachi Internacional Estrella

## 1. Resumen del proyecto

**Tipo de proyecto:** Landing page.

El desarrollador trabajará sobre una **plantilla base de HTML ya existente**. La estructura de secciones de la página **ya está definida por dicha plantilla** y debe respetarse tal cual — este documento no indica qué secciones debe llevar la página. Adicionalmente, ya se entregó un **prompt inicial** para adaptar esa plantilla al negocio; este README complementa ese prompt con la información de marca y los lineamientos visuales obligatorios.

---

## 2. Información del negocio

Datos extraídos del contenido provisto por el cliente y del material en la carpeta `imagenes/` (fotografías de eventos y el emblema de marca).

- **Nombre:** Mariachi Internacional Estrella
- **Rubro:** Grupo de mariachi — música en vivo para serenatas y eventos (se observa participación en bodas, quinceañeras, cumpleaños y eventos religiosos en las fotografías provistas).
- **Teléfono (llamadas):** 55 8333 4281
- **WhatsApp:** 55 6369 0026
- **Red social:** [Facebook](https://www.facebook.com/share/1KqgaUeEY2/)
- **Zona de cobertura / promoción:** Nezahualcóyotl, Chimalhuacán, Los Reyes y zonas cercanas a Cd. Neza.
- **Precio de referencia:** Serenatas desde $1,900 MXN.
- **Diferenciadores de marca (a comunicar en el copy):**
  - Amplio repertorio, animación, presencia escénica y profesionalismo.
  - Grupo joven, con amplia experiencia musical.
  - Experiencia trabajando con figuras públicas y en el extranjero.

---

## 3. Branding

### 3.1 Logotipo / emblema de marca
El emblema oficial de la marca (texto "MARIACHI INTERNACIONAL ESTRELLA" en relieve dorado, con un ícono de estrella, trompeta y violín) se encuentra en el archivo:

`imagenes/670271173_1590146975895480_2230618875480274034_n.jpg`

Este archivo **viene con fondo** (escena fotográfica completa, con integrantes del grupo y arquitectura colonial de fondo). Ver instrucciones en la sección 5.

### 3.2 Paleta de colores
Paleta extraída del emblema dorado y del vestuario (trajes de charro) predominante en las fotografías del negocio (rojo granate como color principal, con bordados dorados):

| Color | HEX | Uso sugerido |
|---|---|---|
| Rojo Mariachi (primario) | `#7A1F2E` | Color de marca principal, fondos de acento, CTAs |
| Dorado Estrella (acento) | `#C9A227` | Detalles, bordes, íconos, hover states — ligado al emblema |
| Negro Profundo (neutro oscuro) | `#14100D` | Texto principal, fondos oscuros |
| Blanco Marfil (neutro claro) | `#FAF5EC` | Fondos claros, espacios en blanco |
| Gris Piedra (neutro secundario) | `#57493C` | Texto secundario, líneas divisorias, fondos sutiles |

### 3.3 Tipografía sugerida
- **Encabezados / display:** *Playfair Display* (serif elegante, coherente con el estilo grabado/dorado del emblema). Alternativa: *Cinzel*.
- **Cuerpo de texto:** *Inter* (sans-serif limpia y minimalista, propia de estética "big tech").

### 3.4 Identidad visual
Fusión entre tradición mexicana (rojo granate, dorado, tipografía serif ornamental del emblema) y una ejecución visual moderna, limpia y corporativa — sin caer en clichés folclóricos saturados de color.

---

## 4. Estilo visual obligatorio

- Estilo **premium, enterprise y de marca corporativa**.
- Nivel **big tech**: elegante y a la vez minimalista.

---

## 5. Efectos y animaciones requeridos

- Efectos visuales y **animaciones de scroll**.
- **Pantalla de carga (preloader)** con spinner + logo del negocio.
- Animaciones en el **título del hero**: efecto máquina de escribir, cambio de color en las letras u otros efectos tipográficos.

---

## 6. Instrucciones sobre assets

- El logo (`imagenes/670271173_1590146975895480_2230618875480274034_n.jpg`) viene **con fondo**: se debe **remover el fondo** antes de usarlo como logo/isotipo en el sitio (preloader, header, favicon, etc.).
- La carpeta `imagenes/` contiene fotografías reales de eventos del grupo (bodas, quinceañeras, cumpleaños, eventos religiosos) y algunos videos de presentaciones en vivo. Varias imágenes son fotos tomadas con celular en formato y resolución no optimizados para web: seleccionar las de mejor calidad/composición y **comprimir/optimizar** (formato web moderno, ej. WebP) antes de publicarlas.
- Los archivos de video en `imagenes/` son pesados (varios superan los 10 MB): si se van a usar, deben comprimirse/optimizarse antes de integrarlos al sitio.

---

## 7. Nota para el desarrollador

Este README y el prompt inicial son el punto de partida, no el resultado final. Se puede **iterar sobre el proyecto usando Claude**, dándole instrucciones las veces que sea necesario, hasta lograr el resultado deseado.

---

## 8. Checklist de trabajo

- [ ] Leer el prompt inicial ya entregado y este README antes de empezar.
- [ ] Remover el fondo del logo (`670271173_1590156342561210_...jpg`… ver ruta exacta arriba) y exportarlo en formato con transparencia (PNG/SVG).
- [ ] Aplicar la paleta de colores de marca (sección 3.2) sobre la plantilla base.
- [ ] Aplicar la tipografía sugerida (sección 3.3) o una equivalente coherente con el estilo premium/enterprise.
- [ ] Incorporar la información del negocio (sección 2: contacto, WhatsApp, redes, zona de cobertura, precio de referencia, diferenciadores) en el copy de la plantilla.
- [ ] Implementar el preloader con spinner + logo.
- [ ] Implementar la animación tipográfica del título del hero (máquina de escribir / cambio de color / similar).
- [ ] Implementar animaciones y efectos de scroll a lo largo de la página.
- [ ] Seleccionar, optimizar y comprimir las imágenes (y video, si aplica) de `imagenes/` antes de integrarlas.
- [ ] Verificar que el resultado final refleje un estilo premium, enterprise y minimalista (nivel big tech).
- [ ] Iterar con Claude Code sobre el resultado hasta cerrar el proyecto.
