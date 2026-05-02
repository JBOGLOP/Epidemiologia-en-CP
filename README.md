# Epidemiología del Cuidado Paliativo · Sesión 7

> **Epidemiologías analíticas en cuidado paliativo: ¿qué dice y qué calla cada diseño sobre las personas que necesitan cuidados paliativos?**

[![Universidad Antonio Nariño](https://img.shields.io/badge/UAN-Maestr%C3%ADa%20en%20Cuidados%20Paliativos-B85C3C)](https://www.uan.edu.co)
[![Sesión](https://img.shields.io/badge/Sesi%C3%B3n-7-7A8B6F)](#)
[![Fecha](https://img.shields.io/badge/Fecha-8%20mayo%202026-D4A547)](#)
[![Modalidad](https://img.shields.io/badge/Modalidad-Aprendizaje%20Activo-8B7B5C)](#)

Repositorio del material didáctico interactivo para la sesión 7 del curso **Epidemiología del Cuidado Paliativo** (cód. 37542002) de la Maestría en Cuidados Paliativos de la Universidad Antonio Nariño. Profesor: **Jorge Wilhelm Bogoya López**.

---

## Tabla de contenidos

- [Pregunta vertebral del curso](#pregunta-vertebral-del-curso)
- [Estructura de la sesión](#estructura-de-la-sesión)
- [Las cuatro estaciones](#las-cuatro-estaciones)
- [Acceso al material en vivo](#acceso-al-material-en-vivo)
- [Anclajes narrativos](#anclajes-narrativos)
- [La cascada de necesidad paliativa no satisfecha](#la-cascada-de-necesidad-paliativa-no-satisfecha)
- [Marco metodológico](#marco-metodológico)
- [Arquitectura técnica](#arquitectura-técnica)
- [Asignación post-sesión](#asignación-post-sesión)
- [Referencias](#referencias)
- [Créditos](#créditos)
- [Licencia](#licencia)

---

## Pregunta vertebral del curso

> *¿Qué dice —y qué calla— el panorama epidemiológico sobre las personas que necesitan cuidados paliativos?*

En esta sesión, la pregunta se refina al diseño analítico:

> *¿Qué dice —y qué calla— el diseño analítico sobre las personas que necesitan cuidados paliativos?*

Cada diseño epidemiológico es como una linterna: alumbra una zona específica de la cascada de necesidad paliativa y deja otras en penumbra. La sesión enseña a leer ambas: lo iluminado y lo silenciado.

---

## Estructura de la sesión

**Duración total:** 120 minutos · **Modelo:** aprendizaje activo · **Instructor talk:** ≤ 30 % del tiempo total

| Bloque | Minutos | Actividad |
|---|---|---|
| 🎯 Apertura y caso disparador | 0–20 | María Luisa y Don Aurelio · pregunta vertebral |
| 🔬 Aprendizaje activo en estaciones | 20–80 | Cuatro estaciones rotativas, 15 min cada una |
| 🤝 Plenaria de integración | 85–110 | Tarjetas de presentación, tabla colectiva, decisiones de diseño |
| 🌅 Cierre | 110–120 | Síntesis y asignación post-sesión |

---

## Las cuatro estaciones

Cada estación está implementada como una página HTML autocontenida con paso a paso interactivo, calculadoras editables, auto-evaluación con retroalimentación pedagógica y registro automático de respuestas en Google Sheets.

### 🟥 [Estación A · El caso que no fue](https://jboglop.github.io/Epidemiologia-en-CP/EstacionA.html)
**Diseño:** Casos y controles clásico · **Color:** terracota

> *¿Qué factores se asocian con admisión tardía a cuidados paliativos en pacientes con cáncer en Bogotá?*

Tabla 2×2 interactiva con cuatro presets, cálculo de OR e IC95 (Woolf), exploración de cuatro sesgos (Berkson, Neyman, memoria, causalidad inversa). **Eslabón que ilumina:** brecha de acceso. **Anclaje narrativo:** María Luisa, ausente del estudio.

### 🟩 [Estación B · El tiempo que sigue](https://jboglop.github.io/Epidemiologia-en-CP/EstacionB_Cohorte.html)
**Diseño:** Cohorte prospectiva · **Color:** salvia

> *¿Cuál es la supervivencia tras inicio de cuidados paliativos domiciliarios en pacientes con EPOC GOLD IV en La Guajira?*

Calculadora de cohorte (incidencia acumulada, densidad de incidencia, RR, RDI, HR conceptual), comparador animado RR vs RDI. Pregunta reflexiva: carta a Don Aurelio. **Eslabón que ilumina:** calidad del morir. **Anclaje narrativo:** Don Aurelio, contrafáctico.

### 🟨 [Estación C · El pasado reconstruido](https://jboglop.github.io/Epidemiologia-en-CP/EstacionC_CohorteHistorica.html)
**Diseño:** Cohorte histórica · **Color:** arena

> *¿Qué proporción de pacientes con EPOC avanzada en Boyacá entre 2019 y 2024 accedió a opioides en su último año de vida?*

Cruce de cuatro fuentes administrativas (RIPS, DANE, INCB, BDUA), calculadora de cobertura cruda, iceberg interactivo del subregistro con análisis de sensibilidad. Pregunta reflexiva: defensa ante un comité de ética. **Eslabón que ilumina:** cobertura del sistema. **Anclaje narrativo:** María Luisa reconstruida.

### 🟧 [Estación D · Lo mejor de dos mundos](https://jboglop.github.io/Epidemiologia-en-CP/EstacionD_NestedCC.html)
**Diseño:** Casos-controles anidado en cohorte · **Color:** ámbar

> *Dentro de la cohorte hipotética del OCCP, ¿qué factores predicen muerte con dolor no controlado en pacientes en cuidados paliativos en Colombia 2023–2025?*

Comparador de tres alternativas (cohorte completa / caso-control clásico / nested), simulador interactivo de muestreo por densidad de incidencia con cálculo de potencia, costo y ahorro relativo. Pregunta reflexiva: recomendación a la maestría sobre el diseño prioritario para investigación paliativa colombiana. **Eslabón que ilumina:** necesidad paliativa estimada. **Anclaje narrativo:** María Luisa y Don Aurelio integrados.

---

## Acceso al material en vivo

| Recurso | URL | Audiencia |
|---|---|---|
| 📐 Estación A | [estacionA.html](https://jboglop.github.io/Epidemiologia-en-CP/EstacionA.html) | Estudiantes |
| 📊 Estación B | [estacionB_Cohorte.html](https://jboglop.github.io/Epidemiologia-en-CP/EstacionB_Cohorte.html) | Estudiantes |
| 🗂️ Estación C | [estacionC_CohorteHistorica.html](https://jboglop.github.io/Epidemiologia-en-CP/EstacionC_CohorteHistorica.html) | Estudiantes |
| 🎯 Estación D | [estacionD_NestedCC.html](https://jboglop.github.io/Epidemiologia-en-CP/EstacionD_NestedCC.html) | Estudiantes |
| 🎤 Presentación maestra | [Presentacion_Maestra_Sesion7.html](https://jboglop.github.io/Epidemiologia-en-CP/Presentacion_Maestra_Sesion7.html) | Docente · plenaria |
| 📡 Dashboard en vivo | [Dashboard_Vivo.html](https://jboglop.github.io/Epidemiologia-en-CP/Dashboard_Vivo.html) | Docente · proyección |

> 💡 Las cuatro estaciones son autocontenidas y funcionan en cualquier navegador moderno. Pueden abrirse desde dispositivos móviles, tabletas o computadores.

---

## Anclajes narrativos

Toda la sesión está organizada alrededor de dos personajes anónimos que representan trayectorias reales de personas vulnerabilizadas en Colombia:

### 👤 María Luisa
Mujer rural del Tolima, diagnosticada con cáncer de cérvix en estadio avanzado, fallecida en su casa sin contacto formal con el sistema de cuidados paliativos. Su muerte no quedó registrada en RIPS. **Aparece en las estaciones A (como ausencia) y C (como reconstrucción posible).**

### 👤 Don Aurelio
Hombre wayúu de La Guajira con EPOC GOLD IV, sin acceso a programas de cuidados paliativos en su departamento (zero servicios disponibles). **Aparece en las estaciones B (como contrafáctico) y D (integrado a cohorte hipotética).**

Estos anclajes encarnan el principio pedagógico central del curso: **personas vulnerabilizadas, no vulnerables** — la vulnerabilidad es estructuralmente producida, no una característica inherente.

---

## La cascada de necesidad paliativa no satisfecha

```
[1] Carga de enfermedad → [2] Necesidad estimada → [3] Cobertura → [4] Brecha → [5] Calidad del morir
       (no iluminada)         (Estación D)         (Estación C)    (Estación A)    (Estación B)
```

Cada estación ilumina **un eslabón distinto** de la cascada. El primer eslabón —carga de enfermedad— queda deliberadamente sin estación dedicada porque requiere diseños transversales poblacionales fuera del alcance analítico de la sesión. Esa ausencia es honestidad metodológica, no descuido.

---

## Marco metodológico

### Estándares no negociables del curso

- 🎯 **Cero datos inventados.** Toda cifra proviene de fuentes verificables (DANE, OCCP, Lancet Commission, INCB) o está rotulada explícitamente como `[DATO POR VERIFICAR]` o `didáctico`.
- 📚 **APA 7.ª edición** en todas las citaciones.
- 🇨🇴 **Español académico colombiano**, tono cálido sin sacrificar rigor.
- ⚖️ **Atribución correcta de la falacia OR vs RR** a Cummings (2009), no a Rothman ni Knol.
- 🔍 **Distinción clara entre confusión y modificación de efecto** en todas las estaciones.

### Fuentes primarias utilizadas
- DANE · Estadísticas Vitales (microdatos públicos)
- Sánchez-Cárdenas et al. · Reportes del Observatorio Colombiano de Cuidados Paliativos (OCCP)
- Pastrana et al. · Estudios sobre opioides y desarrollo paliativo en América Latina
- Knaul et al. · Lancet Commission on Global Access to Palliative Care and Pain Relief
- Worldwide Hospice Palliative Care Alliance (WHPCA)
- International Narcotics Control Board (INCB)
- Woodward, M. (2014). *Epidemiology: Study design and data analysis*. CRC Press.
- Cummings, P. (2009). Methods for estimating adjusted risk ratios. *Stata Journal*, 9(2), 175–196.

---

## Arquitectura técnica

```
┌─────────────────────┐     POST       ┌──────────────────┐
│  Estaciones HTML    │ ─────────────▶ │   Apps Script    │
│  (4 estaciones)     │                │   (Code.gs)      │
└─────────────────────┘                └────────┬─────────┘
                                                │
                                                ▼
                                       ┌──────────────────┐
                                       │  Google Sheets   │
                                       │ actividad_       │
                                       │ analitics        │
                                       └────────┬─────────┘
                                                │
                                                ▼
                                       ┌──────────────────┐
                                       │  Dashboard.gs    │
                                       │  (extracción)    │
                                       └────────┬─────────┘
                                                │
                                                ▼ GET
┌─────────────────────┐                ┌──────────────────┐
│  Dashboard_Vivo     │ ◀───────────── │  Hojas Dashboard │
│  (proyección)       │                │  _Resumen        │
└─────────────────────┘                │  _Quiz           │
                                       │  _Trayectoria    │
                                       └──────────────────┘
```

### Stack tecnológico
- 🌐 **Frontend:** HTML5 + CSS3 + JavaScript vanilla (sin frameworks)
- 📊 **Visualización:** Chart.js 4.4.0, MathJax 3.2.2, SVG nativo, IntersectionObserver API
- ☁️ **Backend:** Google Apps Script (web app pública con token de validación)
- 💾 **Almacenamiento:** Google Sheets como base de datos NoSQL ligera con JSON anidado
- 🚀 **Hosting:** GitHub Pages (este repositorio)

### Características funcionales

✅ Auto-evaluación con retroalimentación pedagógica para todos los distractores
✅ Registro en tiempo real de respuestas con identificación por equipo
✅ Dashboard de proyección con polling cada 20 segundos
✅ Trigger automático horario para refresco de dashboards
✅ Validación por token compartido `UAN_SES7_2026_8MAY`
✅ Sin dependencias de terceros más allá de los CDN públicos especificados

---

## Asignación post-sesión

### "Tu María Luisa metodológica"

Cada estudiante vuelve a su caso `Tu María Luisa` del semestre y decide cuál de los cuatro diseños analíticos sería el más apropiado para responder la pregunta más urgente que ese caso plantea, justificando con tres argumentos metodológicos sustentados.

| Criterio | Especificación |
|---|---|
| 📝 Extensión | 200–300 palabras |
| 📅 Fecha de entrega | Antes del 22 de mayo de 2026 (Sesión 8) |
| 📐 Formato | Word o PDF, APA 7.ª edición |
| 📊 Evaluación | Coherencia entre caso, pregunta y diseño elegido |

---

## Referencias

> **Selección curada del marco bibliográfico.** Para la lista completa, consultar el documento `Guia_Docente_Sesion7.docx`.

Cummings, P. (2009). Methods for estimating adjusted risk ratios. *Stata Journal*, 9(2), 175–196. https://doi.org/10.1177/1536867X0900900201

Knaul, F. M., Farmer, P. E., Krakauer, E. L., et al. (2018). Alleviating the access abyss in palliative care and pain relief — an imperative of universal health coverage: the Lancet Commission report. *The Lancet*, 391(10128), 1391–1454.

Pastrana, T., De Lima, L., Sánchez-Cárdenas, M., Van Steijn, D., & Garralda, E. (2021). Atlas of palliative care in Latin America. IAHPC Press.

Rothman, K. J., Greenland, S., & Lash, T. L. (2008). *Modern epidemiology* (3rd ed.). Lippincott Williams & Wilkins.

Sánchez-Cárdenas, M. A., Moreno-Olarte, J. C., Ortiz-Bonilla, C., et al. (Reportes del Observatorio Colombiano de Cuidados Paliativos · OCCP). Universidad de la Sabana.

Woodward, M. (2014). *Epidemiology: Study design and data analysis* (3rd ed.). CRC Press.

---

## Créditos

**Diseño pedagógico, contenido y dirección académica**
Profesor Jorge Wilhelm Bogoya López
Maestría en Cuidados Paliativos · Facultad de Enfermería
Universidad Antonio Nariño · Bogotá, Colombia

**Implementación técnica**
Construido iterativamente con Anthropic Claude (Claude Opus 4.7) durante el primer semestre de 2026.

---

## Licencia

📚 **Material académico de uso educativo.** Las cuatro estaciones, la presentación maestra y el dashboard pueden reutilizarse en contextos académicos siempre que se respete la atribución al profesor Bogoya López y a la Universidad Antonio Nariño.

🚫 **No autorizado** el uso comercial, la modificación sin atribución, o la redistribución sin permiso explícito del autor.

📊 **Datos numéricos rotulados como `didáctico`** son ilustrativos y no representan estadísticas oficiales sobre Colombia. Las cifras marcadas como `[DATO POR VERIFICAR]` requieren confirmación contra fuentes primarias antes de su uso fuera de este contexto pedagógico.

---

> *"Ningún diseño cuenta toda la historia. Por eso necesitamos varios. Y por eso necesitamos preguntar siempre qué silencia el que escogimos."*
>
> — Frase de cierre · Sesión 7

---

📍 **Universidad Antonio Nariño** · Maestría en Cuidados Paliativos · Sesión 7 · 8 de mayo de 2026
