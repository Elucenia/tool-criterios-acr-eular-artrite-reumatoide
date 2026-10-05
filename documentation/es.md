<!-- ELUCENIA technical documentation · criterios-acr-eular-artrite-reumatoide · es · no clinical/professional/rights approval -->

# Criterios ACR/EULAR 2010 para artritis reumatoide

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/criterios-acr-eular-artrite-reumatoide)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Afectación articular (hinchazón o dolor)

`artic`

- `0` — 1 articulación grande
- `1` — De 2 a 10 articulaciones grandes
- `2` — De 1 a 3 articulaciones pequeñas (con o sin grandes)
- `3` — De 4 a 10 articulaciones pequeñas (con o sin grandes)
- `5` — \> 10 articulaciones (al menos 1 pequeña)

### Serología (factor reumatoide y anti-CCP)

`soro`

- `0` — Ambos negativos
- `2` — Algún título positivo bajo (hasta 3× el límite superior)
- `3` — Algún título positivo alto (\> 3× el límite superior)

### Reactantes de fase aguda (PCR y VSG)

`fase`

- `0` — Ambas normales
- `1` — PCR o VSG alterada

### Duración de los síntomas

`duracao`

- `0` — \< 6 semanas
- `1` — ≥ 6 semanas

## Edición del método

ACR/EULAR 2010: 4 dominios, total 0–10, corte≥6; requiere contexto y exclusiones

## Fórmula documentada

Suma de cuatro dominios (máximo 10): articulaciones (0–5), serología (0–3), fase aguda (0–1), duración de síntomas (0–1). ≥ 6 = artritis reumatoide definida.

Grandes articulaciones: hombros, codos, caderas, rodillas y tobillos. Pequeñas: MCF, IFP, MTF 2ª–5ª, IF del pulgar y muñecas.

## Límites y población

La clasificación ACR/EULAR 2010 exige sinovitis confirmada en al menos una articulación y ausencia de un diagnóstico alternativo que la explique mejor antes de aplicar el punto de corte ≥6/10. Se desarrolló para la sinovitis inflamatoria indiferenciada de nueva aparición. La puntuación aislada, sin estas condiciones, no reproduce los criterios de clasificación.

## Referencias

- [Aletaha D et al. 2010 Rheumatoid arthritis classification criteria: an American College of Rheumatology/European League Against Rheumatism collaborative initiative. Arthritis Rheum, 2010.](https://doi.org/10.1002/art.27584)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
