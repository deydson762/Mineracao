# Roteiro da Apresentação (15 min)

## Slide 1 — Capa
Título do projeto, nomes da dupla, disciplina.

## Slide 2 — Introdução
- Queimadas na Amazônia: problema ambiental
- Base BDQueimadas do INPE: ~975 mil registros em 2025
- Perguntas: onde se concentram os focos? quais condições geram focos intensos?

## Slide 3 — Objetivos e justificativa
- K-Means → hotspots espaciais
- Apriori → regras de associação (clima, estado, mês → intensidade/risco)

## Slide 4 — Base de dados
- Atributos principais: FRP, RiscoFogo, DiaSemChuva, Latitude/Longitude
- Volume, período, fonte (TerraBrasilis/INPE)

## Slide 5 — Metodologia
- Fluxo: pré-processamento → K-Means → Apriori
- Decisões: -999/NaN → mediana, log em FRP, discretização, amostra de 200 mil

## Slide 6 — Resultados: K-Means
- Gráficos cotovelo + silhueta; mapa dos clusters
- Cluster 0 = mais intenso (MT/Amazonas); Cluster 2 = maior risco (sul de MT)

## Slide 7 — Resultados: regras de associação
- Suporte, confiança e lift (explicação rápida)
- Ex.: `{4–7 dias sem chuva, Amazonas, Sem chuva} → {mês 8, risco alto}` lift ≈ 8,7

## Slide 8 — Conclusão
- Achados principais; limitações; trabalhos futuros

## Slide 9 — Referências
- Agrawal & Srikant (1994), MacQueen (1967), Kaufman & Rousseeuw (1990), Han et al. (2011), INPE

## Dicas
- ~1 min por slide + 2 min de perguntas
- Prepare-se para perguntas sobre escolha de k, discretização e lift
- Deixe o notebook aberto para mostrar código se perguntarem
