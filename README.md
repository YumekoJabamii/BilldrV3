# billdr — Landing demos

Tres demos de landing page para [billdr](https://facturador-frontend-delta.vercel.app/), una plataforma de facturación recurrente, conciliación y cobro para empresas de servicios en Argentina.

Estas demos fueron desarrolladas por [RAID](#sobre-raid) como muestra de dirección visual previa a la propuesta formal de trabajo. **No son el entregable final del proyecto** — son tres exploraciones rápidas con enfoques distintos para abrir la conversación sobre estética y tono.

---

## Las tres demos

### v1 — Editorial fintech
Tono editorial con tipografía serif (Fraunces), dark mode con detalles en verde lima. Más expresivo, menos corporativo.

```
billdr-landing.html
```

### v2 — Minimalista tech
Estética alineada al producto actual en UAT: dark mode, paleta azul royal, tipografía sans-serif (Inter). La opción más fiel al lenguaje visual existente de billdr.

```
billdr-landing-v2.html
```

### v3 — Editorial premium
Inspirada en el estilo de [Lucien](https://www.lucien.com/), con tipografía serif italiana (Instrument Serif), marquee horizontal, mockup del dashboard con tratamiento editorial, y detalles tipográficos refinados. Combina la paleta de billdr con un lenguaje visual más sofisticado.

```
billdr-landing-v3.html
```

---

## Cómo verlas

Cada demo es un archivo HTML autocontenido. Para abrirlas:

**Opción 1 — Localmente**

Cloná el repositorio y abrí cualquiera de los archivos `.html` en el navegador.

```bash
git clone https://github.com/[usuario]/billdr-landings.git
cd billdr-landings
```

Después abrís cualquiera de los tres archivos directamente en el navegador.

**Opción 2 — Online**

Si publicaste con GitHub Pages, las demos están disponibles en:

- v1: `https://[usuario].github.io/billdr-landings/billdr-landing.html`
- v2: `https://[usuario].github.io/billdr-landings/billdr-landing-v2.html`
- v3: `https://[usuario].github.io/billdr-landings/billdr-landing-v3.html`

---

## Stack técnico

Las tres demos están hechas con HTML, CSS y JavaScript vanilla. Sin frameworks, sin build step, sin dependencias.

- Tipografías servidas desde Google Fonts
- Animaciones con CSS y la API `IntersectionObserver`
- Responsive en desktop, tablet y mobile
- Sin librerías externas

Cualquier navegador moderno las renderiza sin problema.

---

## Aclaración importante

Estas demos fueron hechas en pocas horas como muestra de criterio visual. **No están pulidas ni testeadas en todos los dispositivos**, no nacen de un proceso completo de discovery con el cliente, y no usan los textos definitivos del producto.

La landing final, en caso de avanzar, se construye con un proceso completo:

1. Reunión inicial para definir objetivos y audiencia
2. Primer diseño de la landing
3. Dos rondas de feedback
4. Desarrollo
5. Cierre y entrega

---

## Sobre RAID

[RAID](https://raid.ar) desarrolla software a medida para pymes y emprendimientos en Argentina. Nos especializamos en sitios web, aplicaciones web y sistemas internos para equipos chicos que quieren profesionalizar su operación.

- Desarrollo web a medida
- PWAs (Progressive Web Apps)
- Sistemas a medida
- Mantenimiento mensual

**Equipo:** Agustín (comercial y producto) + Moro (desarrollo y diseño).

Para consultas: [hola@raid.ar](mailto:hola@raid.ar)

---

## Licencia

Estas demos fueron creadas para uso exclusivo de billdr. El código y el diseño se entregan como parte de una propuesta comercial y no están licenciados para uso por terceros.

© 2026 RAID — Buenos Aires, Argentina
