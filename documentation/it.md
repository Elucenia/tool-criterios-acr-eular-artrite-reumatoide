<!-- ELUCENIA technical documentation · criterios-acr-eular-artrite-reumatoide · it · no clinical/professional/rights approval -->

# Criteri ACR/EULAR 2010 per l’artrite reumatoide

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/criterios-acr-eular-artrite-reumatoide)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Coinvolgimento articolare (gonfiore o dolore)

`artic`

- `0` — 1 grande articolazione
- `1` — Da 2 a 10 grandi articolazioni
- `2` — Da 1 a 3 piccole articolazioni (con o senza grandi articolazioni)
- `3` — Da 4 a 10 piccole articolazioni (con o senza grandi articolazioni)
- `5` — \> 10 articolazioni (almeno 1 piccola)

### Sierologia (fattore reumatoide e anti-CCP)

`soro`

- `0` — Entrambi negativi
- `2` — Almeno un titolo positivo basso (fino a 3× il limite superiore)
- `3` — Almeno un titolo positivo alto (\> 3× il limite superiore)

### Indici di fase acuta (PCR e VES)

`fase`

- `0` — Entrambe normali
- `1` — PCR o VES alterata

### Durata dei sintomi

`duracao`

- `0` — \< 6 settimane
- `1` — ≥ 6 settimane

## Edizione del metodo

ACR/EULAR 2010: 4 domini, totale 0–10, soglia≥6; richiede contesto ed esclusioni

## Formula documentata

Somma di quattro domini (massimo 10): articolazioni (0–5), sierologia (0–3), fase acuta (0–1), durata sintomi (0–1). ≥ 6 = artrite reumatoide definita.

Grandi articolazioni: spalle, gomiti, anche, ginocchia e caviglie. Piccole: MCF, IFP, MTF 2ª–5ª, IF del pollice e polsi.

## Limiti e popolazione

La classificazione ACR/EULAR 2010 richiede una sinovite confermata in almeno un’articolazione e l’assenza di una diagnosi alternativa che la spieghi meglio prima di applicare la soglia ≥6/10. È stata sviluppata per la sinovite infiammatoria indifferenziata di nuova presentazione. Il punteggio da solo, senza queste condizioni, non riproduce i criteri di classificazione.

## Riferimenti

- [Aletaha D et al. 2010 Rheumatoid arthritis classification criteria: an American College of Rheumatology/European League Against Rheumatism collaborative initiative. Arthritis Rheum, 2010.](https://doi.org/10.1002/art.27584)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Classifica come artrite reumatoide definita (≥ 6 punti)


### 2

Classifica come artrite reumatoide definita (≥ 6 punti)


### 3

Non soddisfa i criteri di classificazione (< 6 punti)

Non esclude l’artrite reumatoide: rivalutare nel tempo.

