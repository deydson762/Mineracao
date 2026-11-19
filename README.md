# Projeto de Mineração de Dados — Focos de Queimadas no Brasil (2025)

Análise de padrões espaciais e regras de associação em dados de queimadas do INPE (BDQueimadas), utilizando **K-Means** para identificar hotspots e **Apriori** para minerar regras entre atributos dos focos.

## Estrutura

- `Projeto.ipynb` — relatório completo (introdução, justificativa, revisão, metodologia, resultados, conclusão, referências) com todo o código executado
- `bdqueimadas_2025-01-01_2025-12-31.csv` — base de dados do INPE

## Como executar

```bash
pip install pandas numpy matplotlib seaborn scikit-learn mlxtend jupyter ipykernel
jupyter notebook Projeto.ipynb
```

Fonte dos dados: [TerraBrasilis – BDQueimadas (INPE)](https://terrabrasilis.dpi.inpe.br/queimadas/bdqueimadas/#mapa)

## Equipe

Deydson — Mineração de Dados, 2026
