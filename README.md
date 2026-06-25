# Projeto de Redes Neurais

Projeto acadêmico desenvolvido no Centro de Informática da UFPE (CIn/UFPE) para a disciplina de mestrado em Redes Neurais.

## Sobre o projeto

Este repositório implementa o modelo **NCTD**, descrito no artigo [Nature Scientific Reports](https://www.nature.com/articles/s41598-025-01568-0), e reúne experimentos voltados à avaliação de desempenho em **datasets desbalanceados**.

Além da versão base do NCTD, o projeto avalia variantes propostas durante o desenvolvimento, incluindo **NCTD Attention (SE)**, **NCTD Asymmetric Kernels**, **NCTD Dilated Convolutions** e **NCTD Residual**. O repositório também inclui uma etapa de enriquecimento de dados com **GAN/CTGAN**, utilizada como extensão experimental e não como parte do artigo original.

Os experimentos utilizam os datasets **Adult Income**, **Student**, **Statlog**, **Maintenance** e **Stroke**.

## Estrutura do repositório

- `data/`: contém os datasets utilizados nos experimentos e os artefatos gerados durante o processamento e a avaliação.
- `project_data.ipynb`: preparação dos dados, análise de desbalanceamento e enriquecimento sintético.
- `project_models.ipynb`: implementação dos modelos e execução dos experimentos comparativos.
- `project_results.ipynb`: análise e consolidação dos resultados obtidos.
- `pyproject.toml`: definição das dependências e configuração do projeto.
- `uv.lock`: arquivo de lock do ambiente para reprodução das dependências.

## Uso

A execução sugerida do projeto segue a ordem abaixo:

1. `project_data.ipynb`
2. `project_models.ipynb`
3. `project_results.ipynb`

## Observação

Os resultados consolidados dos experimentos podem ser encontrados nos artefatos gerados no diretório `data/`, incluindo arquivos auxiliares produzidos ao longo da análise.
