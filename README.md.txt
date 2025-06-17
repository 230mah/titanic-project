## Descrição
Este projeto tem como objetivo prever quais passageiros sobreviveram ao naufrágio do Titanic, utilizando aprendizado de máquina.

## Estrutura de Pastas
- `data/raw/`: arquivos originais do Kaggle (`train.csv`, `test.csv`)  
- `data/processed/`: dados processados e arquivos de submissão  
- `notebooks/`: notebooks com as etapas do projeto  
  - `01_exploracao.ipynb`  
  - `02_preprocessamento.ipynb`  
  - `03_modelagem.ipynb`  
  - `04_submissao.ipynb`

## Como rodar
1. Execute os notebooks na ordem:  
   - `01_exploracao.ipynb`  
   - `02_preprocessamento.ipynb`  
   - `03_modelagem.ipynb`  
   - `04_submissao.ipynb`  

2. O arquivo de submissão será gerado em `data/processed/submission.csv`.

## Submissão no Kaggle
- Acesse https://www.kaggle.com/c/titanic/submit  
- Envie o arquivo `submission.csv` para avaliação.

## Melhorias futuras
- Implementar validação cruzada  
- Testar diferentes modelos e tuning  
- Analisar importância das features  
- Automatizar pipeline com scripts
