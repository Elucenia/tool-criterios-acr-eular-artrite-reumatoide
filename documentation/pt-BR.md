<!-- ELUCENIA technical documentation · criterios-acr-eular-artrite-reumatoide · pt-BR · no clinical/professional/rights approval -->

# Critérios ACR/EULAR 2010 para artrite reumatoide

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/criterios-acr-eular-artrite-reumatoide)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Acometimento articular (edema ou dor)

`artic`

- `0` — 1 grande articulação
- `1` — 2 a 10 grandes articulações
- `2` — 1 a 3 pequenas articulações (com ou sem grandes)
- `3` — 4 a 10 pequenas articulações (com ou sem grandes)
- `5` — \> 10 articulações (ao menos 1 pequena)

### Sorologia (fator reumatoide e anti-CCP)

`soro`

- `0` — Ambos negativos
- `2` — Algum positivo em título baixo (até 3× o limite superior)
- `3` — Algum positivo em título alto (\> 3× o limite superior)

### Provas de fase aguda (PCR e VHS)

`fase`

- `0` — Ambas normais
- `1` — PCR ou VHS alterada

### Duração dos sintomas

`duracao`

- `0` — \< 6 semanas
- `1` — ≥ 6 semanas

## Edição do método

ACR/EULAR 2010:4 domínios, total 0–10, corte≥6; requer contexto e exclusões

## Fórmula documentada

Soma dos quatro domínios (máximo 10): articulações (0 a 5), sorologia (0 a 3), provas de fase aguda (0 a 1) e duração dos sintomas (0 a 1). Escore ≥ 6 = artrite reumatoide definida.

Grandes articulações: ombros, cotovelos, quadris, joelhos e tornozelos. Pequenas: metacarpofalângicas, interfalângicas proximais, 2ª a 5ª metatarsofalângicas, interfalângica do polegar e punhos.

## Limites e população

A classificação ACR/EULAR 2010 exige sinovite confirmada em pelo menos uma articulação e ausência de diagnóstico alternativo que a explique melhor, antes de aplicar o corte ≥6/10. Foi desenvolvida para o contexto de sinovite inflamatória indiferenciada de apresentação nova. O escore isolado, sem essas condições, não reproduz os critérios de classificação.

## Referências

- [Aletaha D et al. 2010 Rheumatoid arthritis classification criteria: an American College of Rheumatology/European League Against Rheumatism collaborative initiative. Arthritis Rheum, 2010.](https://doi.org/10.1002/art.27584)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
