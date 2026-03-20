# Manual420 — ChatGPT Config (interno)

**Versión:** v1.0.1

> **Regla de versionado (obligatoria):**
> - No es necesario subir la versión en cada edición.
> - Subimos versión **al cerrar una sesión de trabajo** (una sesión puede durar un día o varios días consecutivos, a criterio del asistente).
> - Cambios directos míos al archivo dentro de una sesión: se acumulan y luego subir **minor** al cierre (v1.0.0 → v1.0.1…).
> - Cambios “mayores” (re-estructura, nuevas secciones grandes, cambios de política): los defines tú y/o me pides subir **major**.

> **Propósito de este archivo:** reglas y meta‑instrucciones para producir y mantener el contenido del repositorio **Manual420** con consistencia.
> **Principio operativo:** estas configs son la “información genética” del directorio. Si hay dudas, **desconfía de memorias** y vuelve aquí: esta config debe permitir recrear el estilo, la estructura, el workflow y los estándares aunque “se olvide todo”.
> **Importante:** aquí NO va el contenido final del manual salvo ejemplos cortos de tono o estructura. El contenido público vive en `README.md`, `es/README.md` y, más adelante, en los `.md` específicos que se creen.

---

## 0) Identidad y propósito

- Nombre del repositorio/proyecto: **Manual420**.
- Nombre público/editorial preferido: **Manual 4/20 🌿**.
- Sitio público: **https://manual420.barranco.life**
- Relación con otros repos/sitios:
  - **420** = Encuentro Nacional 4/20, espacios anfitriones, historial, protocolo cultural replicable.
  - **420.barranco.life** = sitio público del Encuentro Nacional 4/20²⁶ 🌿.
  - **Manual420** = manual abierto, cívico y educativo, con vida propia.
  - **Voluntariado Barranco** = proyecto hermano; usar públicamente **https://voluntariado.barranco.life/** cuando corresponda.
- El manual no es un apéndice del evento: puede circular, crecer, imprimirse y usarse independientemente.
- El idioma canónico inicial es **español**.
- La raíz del repo se mantiene en **inglés** para favorecer internacionalización y consistencia con otros repos.

### Nombre público de referencia del encuentro asociado

**Encuentro Nacional 4/20²⁶ Pro-Legalización 🌿 Celebración cultural replicable de ingreso y participación libre**

### Propósito editorial del manual

Construir un manual abierto y serio sobre cultura 4/20, legalidad, convivencia, reducción de estigma y organización responsable de encuentros; útil para ciudadanos, espacios anfitriones, voluntarios, medios y cualquier persona que quiera informarse o aportar.

---

## 1) Principios rectores del manual

- **Abierto:** cualquiera puede aportar links, archivos, comentarios, contactos y observaciones útiles.
- **Curado:** no todo lo que entra se publica tal cual; el manual integra y ordena.
- **Citable:** el contenido debe tender a estar respaldado por referencias verificables.
- **Sobrio:** evitar tono panfletario, dogmático o simplista.
- **Útil:** priorizar información accionable, contextual y reutilizable.
- **No incriminante:** no incluir apología del delito, instrucciones para delinquir, ni guías para evadir controles.
- **Replicable:** siempre que se pueda, escribir pensando en que otros puedan adaptar el modelo a su ciudad, espacio o país.

---

## 2) Tono y voz

### Tono base

Claro, humano, sobrio y culturalmente maduro.

El manual no debe sonar ni a propaganda, ni a paper académico frío, ni a folleto improvisado. Debe sentirse como una guía ciudadana seria, abierta y bien cuidada.

### Debe ser

- Claro y directo.
- Sereno y no reactivo.
- Informativo sin tecnicismo innecesario.
- Culturalmente amplio: no hablar solo para “la gente 420”.
- Responsable: libertad, sí; con límites claros.
- Persuasivo por madurez, no por confrontación.

### Evitar

- Tono burlón, adolescente o excesivamente interno.
- Jerga innecesaria si excluye a lectores nuevos.
- Grandilocuencia activista o mesiánica.
- Afirmaciones legales o médicas sin respaldo.
- Lenguaje que parezca instrucción para cometer actos ilícitos.

### Frase madre de contexto cultural

> El 4/20 muestra que sí es posible una comunidad espontánea, diversa, colaborativa y cuidadosa del espacio. Voluntariado Barranco busca cultivar durante todo el año esa misma posibilidad: una forma más libre, responsable y humana de convivir, organizarse y crear en común.

Usar esta frase o su espíritu como brújula conceptual cuando haga falta conectar el manual con el ecosistema Barranco/Voluntariado, sin forzar esa relación en todas las páginas.

---

## 3) Fronteras editoriales y legales

- El manual debe ayudar a **desestigmatizar** y promover una conversación sobre legalización con **madurez, libertad y límites claros**.
- El manual puede hablar de:
  - cultura 4/20
  - antecedentes históricos
  - usos medicinales e industriales
  - situación legal
  - comparación internacional
  - convivencia y reducción de riesgos
  - organización responsable de encuentros
  - directorios de apoyo
- El manual puede ayudar a desestigmatizar y volver más legible el tema en la conversación pública, pero sin funcionar como propaganda.
- El manual no debe incluir:
  - apología del delito
  - instrucciones para ocultar conductas ilegales
  - estrategias para “ganarle” a controles o autoridades
  - consejos médicos o legales presentados como definitivos sin fuente y sin cautela

### Regla de seguridad narrativa

Cuando haya temas delicados, priorizar formulaciones del tipo:
- “marco legal vigente”
- “responsabilidad individual”
- “convivencia y cuidado del espacio”
- “límites claros”
- “organización culturalmente defendible, legalmente prudente y socialmente persuasiva”

---

## 4) Estructura inicial del repo

Estructura mínima actual esperada:

- `README.md`
- `LICENSE`
- `es/README.md`
- `es/manual/README.md`
- `ChatGPT.md`

### Convención de idiomas

- La **raíz** contiene la puerta de entrada breve en inglés.
- `es/README.md` es la versión canónica inicial del manual.
- No crear más archivos de idioma hasta que haya suficiente contenido real.
- Evitar fragmentar el manual en demasiados `.md` demasiado pronto.

### Regla de crecimiento

- Mientras el contenido siga siendo corto, mantenerlo concentrado en pocos archivos.
- Recién separar capítulos cuando el tamaño o la claridad realmente lo pidan.
- Menos navegación al inicio; más claridad.

---

## 5) GH Pages

- Pensar el repo desde el inicio para **GH Pages**.
- El sitio público actual es **https://manual420.barranco.life**.
- La experiencia principal debe arrancar en español.
- Puede usarse una de estas dos estrategias más adelante:
  - root breve con redirección a `/es/`
  - root breve y navegación visible hacia la versión en español
- No complicar esta decisión antes de tener el contenido mínimo estable.

### Analítica

- GoatCounter se integra a las Pages generadas.
- Por simplicidad, puede hardcodearse el script en un solo lugar si hace falta, siempre que no obligue a tocar los `.md`.
- Si el sitio usa Jekyll/theme, evitar soluciones que rompan el layout del theme por inyectar analytics.

### Estética esperada

- Sobria, casi institucional.
- Cero estética de “folleto de fumones”.
- Más “manual ciudadano/cultural” que “promo de evento”.

---

## 6) Cómo aportar (principio fundador)

En esta etapa temprana, el manual depende mucho de aportes externos: links, archivos, comentarios, contactos, ideas de capítulos, observaciones y materiales históricos.

### Canales de aporte permitidos

#### GitHub Issues
Canal visible y preferido para:
- links
- sugerencias
- correcciones
- ideas de secciones
- archivos simples
- discusiones públicas

#### Email
**manual420@barranco.life**

Para:
- material sensible
- documentos no públicos de entrada
- contactos delicados
- aportes largos

#### WhatsApp
- Número: **72041572**
- Link directo: **https://api.whatsapp.com/send?phone=59172041572**

WhatsApp es un canal válido y visible desde el inicio, especialmente porque el usuario lo atiende más que el email. No es obligatorio “migrar” el aporte luego al correo si no hace falta; lo importante es no perderlo y curarlo bien.

### Qué tipo de aportes buscamos

- leyes, normas, fallos, reglamentos o análisis legales
- artículos, investigaciones o estudios
- antecedentes de eventos 4/20
- materiales históricos o culturales
- contactos de abogados, médicos, activistas, periodistas o espacios
- ideas de capítulos o secciones
- correcciones o matices sobre borradores
- experiencias útiles sobre convivencia, organización y cuidado del espacio

### Regla de recepción

Los aportes pueden llegar en crudo. El trabajo del repo es integrarlos con criterio.

---

## 7) Links y contacto canónicos

- Sitio público del manual: **https://manual420.barranco.life**
- Email principal del proyecto: **manual420@barranco.life**
- WhatsApp directo: **https://api.whatsapp.com/send?phone=59172041572**
- Sitio público relacionado del encuentro: **https://420.barranco.life**
- Proyecto Cultural Barranco (Maps): **https://goo.gl/maps/iWB6R5HZnREL7ALKA**
- Voluntariado Barranco (sitio): **https://voluntariado.barranco.life/**
- Comunidad Barranco (WhatsApp): **https://chat.whatsapp.com/EUNIisAbWSrB4tqySGtimQ**
- Voluntariado Barranco (WhatsApp): **https://chat.whatsapp.com/LUlxChjwX6qIcdwRdaCGbm**

> Regla: cuando un documento invite a aportar, participar o sumarse, debe incluir el canal adecuado para hacerlo.

---

## 8) Reglas de estilo en Markdown

### Callouts

- No usar sintaxis tipo `[!NOTE]`, `[!IMPORTANT]`, etc. en documentos públicos del sitio.
- Preferir blockquotes simples con emoji, por ejemplo:
  - `> 🌿 ...`
  - `> ⚠️ ...`
  - `> ℹ️ ...`

### Breadcrumbs

Cuando un documento ya pertenezca claramente a una sección o sub-sección, incluir breadcrumb en la parte superior en formato Markdown, así:

`Inicio > <Sección> > <Nombre>`

Cada parte debe ser un link clickeable hacia su ubicación correspondiente.

Mientras el repo siga mínimo y el contenido esté concentrado, no forzar breadcrumbs innecesarios si solo agregan ruido.

### Links

- En documentos Markdown, preferir links **dentro del texto**.
- Minimizar URLs sueltas dentro del cuerpo.
- Cuando se compartan enlaces directos al pie, el pie debe ser **solo URL** si aplica.
- Si el documento invita a acción, incluir links relevantes y suficientes.

### URLs canónicas al pie

- Si un documento público usa link canónico al final, dejar una sola línea URL al pie apuntando al archivo en GitHub.
- Mantener consistencia entre documentos del mismo repo.

### Nombres de archivo

- Mantener nombres simples y consistentes.
- No crear nombres rebuscados o hipergranulares demasiado pronto.
- Si luego se crean documentos específicos, usar convenciones consistentes con el resto del ecosistema.

---

## 9) Relación con el repo 420

- **420** sigue siendo la casa del Encuentro: historial, espacios anfitriones, ediciones, protocolo y narrativa del evento.
- **420.barranco.life** es la referencia pública cuando el contexto es de lectura/navegación, no el repo técnico.
- **Manual420 / Manual 4/20 🌿** es la pieza educativa/cívica que puede citar, enlazar y apoyar al Encuentro, pero no depende de él para existir.
- Debe haber links cruzados entre ambos sitios cuando corresponda.
- Evitar duplicación innecesaria: si algo pertenece claramente al Encuentro, vive en `420`; si es conocimiento reusable y duradero, vive en `Manual420`.

---

## 10) Workflow de iteración con MAYÚSCULAS

- Si en un documento compartido (Xcode/canvas/markdown) aparecen MAYÚSCULAS, asumir que son **marcadores de iteración**.
- Las MAYÚSCULAS **no** son copy final: son notas tipo “marcador rojo” que guían la siguiente pasada.
- Yo puedo agregar MAYÚSCULAS para pedir input puntual (ej: `LINK_POR_DEFINIR`, `CITA_FALTA`, `CONFIRMAR_NOMBRE`).
- En la siguiente iteración, resolver/reemplazar las MAYÚSCULAS y dejar el texto limpio.
- Cuando el usuario diga “Iteremos”, asumir que hay MAYÚSCULAS que resolver y no cambiar el resto del texto salvo lo marcado.
- Si el flujo falla, priorizar preservar MAYÚSCULAS y hacer la siguiente iteración sin borrar notas.
- Regla anti-pérdidas: nunca borrar párrafos o secciones completas salvo que una MAYÚSCULA lo pida explícitamente.

---

## 11) Workflow recomendado para archivos sensibles

- Preferir: iterar en el archivo real con MAYÚSCULAS y una pasada por vez.
- Canvas temporal: solo si tú lo pides o si el archivo es muy sensible y conviene aislar una propuesta primero.
- Editar **1 archivo por pasada** cuando estemos afinando estructura, links o navegación.
- No expandir la arquitectura del repo prematuramente si todavía no hay contenido que lo justifique.

---

## 12) Checklist editorial

Antes de entregar texto para `Manual420`, revisar:

- ¿Suena como manual ciudadano/cultural y no como panfleto?
- ¿Mantiene sobriedad, claridad y utilidad?
- ¿Evita apología del delito y consejos riesgosos?
- ¿Distingue bien entre información general, marco legal y opinión?
- ¿Invita a aportar de forma clara cuando corresponde?
- ¿Incluye links o canales útiles si llama a la acción?
- ¿Está escrito para poder crecer y reutilizarse?
- ¿No está fragmentando de más el contenido demasiado pronto?
- ¿Los links al Encuentro apuntan a **https://420.barranco.life** cuando el contexto es público?
- ¿El nombre visible es **Manual 4/20 🌿** cuando el contexto es editorial/público?
- ¿Se evitó la palabra “caricatura” en favor de “prejuicios” o “reducciones simplistas”?

---

## 13) Contenido para migrar a config padre (aplicable a otras iniciativas)

- La idea de “configs como genética”: reglas para recrear outputs aunque se pierda contexto.
- Workflow de iteración con MAYÚSCULAS.
- Regla de versionado por sesión.
- Regla de “documentos que circulan solos”: incluir links clave cuando inviten a acción.
- Reglas de links en Markdown: preferir links embebidos en texto y minimizar URLs sueltas.
- Regla de “un archivo por pasada” cuando haya riesgo de que cambios no se apliquen.
- Criterio de estructura mínima al inicio y expansión posterior solo cuando el contenido lo pida.

---

## 14) Nota operativa actual

Primera fase del repo:
- estructura mínima ya desplegada
- README raíz breve en inglés
- `es/README.md` como puerta de entrada en español
- `es/manual/README.md` como lectura pública principal del manual
- apertura explícita a aportes externos
- crecimiento rápido, pero sin perder sobriedad ni norte editorial
- revisión posterior de si conviene partir el manual en más archivos o mantenerlo aún concentrado
