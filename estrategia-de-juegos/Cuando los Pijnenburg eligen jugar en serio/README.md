# AAE · Teoría de juegos en la gobernanza corporativa

Estudio analítico que aplica cuatro herramientas de teoría de juegos a la
transición de gobierno en **AAE — Advanced Automated Equipment** (Helmond,
Países Bajos), cuando **Manon Pijnenburg** asume la CEO del grupo el
**1 de julio de 2026**.

## Contenido del paquete

| Archivo       | Qué es                                                  |
|---------------|---------------------------------------------------------|
| `index.html`  | Página autocontenida con la visualización completa (~50 KB). |
| `README.md`   | Este archivo.                                           |

## Cómo abrir la página

`index.html` es un único archivo HTML sin dependencias locales. Funciona con
cualquiera de estas opciones:

1. **Doble clic** sobre `index.html` → se abre en tu navegador.
2. **Clic derecho → "Abrir con"** → Chrome / Firefox / Safari / Edge.
3. **Arrastra** el archivo a una ventana del navegador ya abierta.

**Requisitos:** conexión a internet la primera vez (carga Google Fonts:
*DM Serif Display*, *Outfit*, *JetBrains Mono*). Después funciona offline.

La página es responsiva: se adapta de móvil a desktop. Imprimible en A4 si
quieres guardarla en PDF.

## Estructura de la página

1. **Hero** — Título + 4 estadísticas clave (€150 M → €1 B de facturación,
   550 → 1.000 empleados, fundación 1976, cuatro propietarios).
2. **Línea del tiempo 1976 → 2026** — Siete hitos desde la fundación de
   William Pijnenburg hasta la sucesión de Manon.
3. **Diagrama de gobernanza** — Cuatro capas (propietarios → family council
   → executive board → operaciones) con leyenda de autoridad formal vs.
   autoridad real.
4. **Cuatro movimientos de teoría de juegos**, cada uno con su color:
   - *Esquemas de incentivos* (Principal–Agente) — Holmstrom–Milgrom,
     tournament theory, KPI mixtos 60 % EBITDA + 40 % no financieros.
   - *Integración vertical* (Hold-up · Make-or-buy) — Klein–Crawford–
     Alchian, MFN clauses, subastas Vickrey, screening menu.
   - *Composición del comité ejecutivo* (Voting games) — Índice de Banzhaf,
     votación secuencial para extraer información asimétrica.
   - *Asignación de poder formal* (Veto players · Decision rights) —
     Tsebelis, Aghion–Tirole, golden shares, dual class.
5. **Síntesis** — Cuatro propiedades del equilibrio acoplado en un juego
   dinámico con información incompleta y jugadores heterogéneos.

## Caso de referencia

AAE — Advanced Automated Equipment, Helmond, Noord-Brabant (Países Bajos).
Fundada en **1976** por **William Pijnenburg**. Fabricante de alta precisión
de máquinas y módulos automatizados para clientes como **ASML**, **Thermo
Fisher**, **Pfizer** y **Eli Lilly** en sectores semiconductor y médico.

Tras el fallecimiento de William en **julio de 2016**, la empresa pasó a
manos de su esposa y sus tres hijos (**Manon**, **Mark**, **Koen**). El
directivo externo **Frank Mulders** dirigió la compañía entre 2016 y 2026.
El **1 de julio de 2026**, Manon asume la CEO del AAE Group; Mulders pasa
a **VP Global Operations** y Director de AAE Europa.

A septiembre de 2026: ~550 empleados en Helmond → objetivo 1.000;
~€150 M de facturación → objetivo €1 B.

### Fuentes principales

- *de Ondernemer* — «10 jaar na overlijden van haar vader volgt Manon (40)
  hem op als ceo van hun familiebedrijf».
  <https://www.deondernemer.nl/actueel/familiebedrijf/aae-familiebedrijf-manon-pijnenburg-hightech~81fb8d9>
- *LINK magazine* — «AAE versterkt leiderschap en bereidt zich voor op
  volgende internationale groeifase».
  <https://linkmagazine.nl/aae-versterkt-leiderschap-en-bereidt-zich-voor-op-volgende-internationale-groeifase/>
- *de Ondernemer* — «Op naar 1.000 medewerkers en 1 miljard omzet».
  <https://www.deondernemer.nl/innovatie/aae-helmond-hightech-frank-mulders-manon-pijnenburg~d5935d3>
- *AAE* — Our History.
  <https://www.aae-na.tech/our-story/our-history>

## Marco teórico citado

| Concepto | Referencia |
|---|---|
| Principal–Agent (contrato lineal) | Holmstrom & Milgrom (1987) |
| Tournament theory | Lazear & Rosen (1981) |
| Multitasking principal–agent | Holmstrom (1991) |
| Hold-up problem | Klein, Crawford & Alchian (1978) |
| Screening / signaling | Rothschild & Stiglitz (1976); Spence (1973) |
| Subasta de segundo precio | Vickrey (1961) |
| Voting games & power indices | Banzhaf (1965); Shapley–Shubik (1954) |
| Veto players | Tsebelis (2002) |
| Autoridad formal vs. real | Aghion & Tirole (1997) |
| Mechanism design | Myerson (1979); Maskin (1977) |

## Notas técnicas

- **Tipografía:** DM Serif Display (titulares), Outfit (cuerpo), JetBrains
  Mono (etiquetas y datos).
- **Paleta:** cobre `#c97b3f` sobre crema `#f7f5f0`, con acentos secundarios
  por dimensión de teoría de juegos.
- **Sin JavaScript:** toda la interactividad (si la hubiera) está en HTML y
  CSS. Los SVG están inline.
- **Sin trackers, sin cookies, sin CDNs externos** más allá de Google Fonts.

## Licencia y atribución

Análisis原创 sobre un caso de dominio público. Puedes compartir, reimprimir
o adaptar libremente citando la fuente original (*de Ondernemer*, 2026).

---

*Mavis · game theory applied · septiembre 2026*