# Minicurso - Expressão Diferencial (RNA-seq)

## Lesson overview 📚

|  |  |
| :--- | :--- |
| **Licença** | [Creative Commons Attribution Share Alike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/deed.en) |
| **Público-alvo** | Alunos de graduação e pós-graduação. |
| **Nível** | **Iniciante/Intermediário** |
| **Tempo estimado** | 240 minutos (4 horas) |

---

## 📖 Descrição do Curso

Este repositório contém o material prático e scripts de R para o curso **"Análise de Expressão Diferencial e Funcional (RNA-seq)"**. Esta análise utiliza dados de expressão gênica (`GSE60450`) para demonstrar um pipeline de análise de RNA-seq.

O curso cobre as seguintes etapas essenciais em bioinformática:

1.  **Sanidade e Exploração de Dados:** Importação, transformação VST e análise exploratória (**PCA** e **Clusterização Hierárquica**) para avaliar a qualidade e a estrutura dos dados.
2.  **Análise de Expressão Diferencial (DGE):** Aplicação do modelo Binomial Negativo com o pacote **DESeq2** e interpretação dos contrastes de interesse.
3.  **Representações Gráficas:** Criação de visualizações de alta qualidade para publicação, incluindo **Heatmaps** e **Volcano Plots** customizados. 
4.  **Interpretação Funcional:** Análise de Enriquecimento Funcional (**KEGG Pathways**) usando `clusterProfiler` para identificar vias biológicas alteradas.
5.  **Análise de Redes:** Construção e visualização de **Redes de Interação Proteína-Proteína (PPI)** a partir da API do STRINGdb.

---

## ➡ Resultados de Aprendizagem

Ao final do curso, os alunos serão capazes de:

1.  **Processar** e **explorar** dados de contagem de RNA-seq usando pacotes essenciais como `DESeq2` e `PCAtools`.
2.  **Executar** o pipeline completo do DESeq2, testando contrastes de interesse e interpretando as métricas ($\text{LFC}$ e $\text{padj}$).
3.  **Gerar** gráficos de qualidade de publicação, como Volcano Plots e Heatmaps, aplicando temas profissionais.
4.  **Realizar** Análise de Enriquecimento Funcional (KEGG) e **interpretar** as vias biológicas significativas.
5.  **Construir** Redes de Interação Proteína-Proteína (PPI) utilizando a API do STRINGdb e ferramentas de visualização como `igraph` e `RedeR`.

---

## ⚙  Requisitos de Software

Participantes devem ter um laptop com uma versão recente do **R** ($\ge 4.0$) e **RStudio** instalados.

### 📦 Principais Dependências de Pacotes (R/Bioconductor):

| Categoria | Pacotes |
| :--- | :--- |
| **DGE** | `DESeq2` |
| **Exploração/Visualização** | `tidyverse` (`dplyr`, `ggplot2`), `PCAtools`, `pheatmap`, `ggrepel` |
| **Anotação/Funcional** | `clusterProfiler`, `AnnotationDbi`, `org.Mm.eg.db` |
| **Redes** | `RCurl`, `igraph`, `RedeR` |

---

## 🙏 Agradecimentos

* Bioinformatics Multidisciplinary Environment (BioME - IMD/UFRN)
* Postgraduate Program in Bioinformatics (PPg-Bioinfo - UFRN)
* **Agradecimento especial:** O material prático utiliza dados públicos do estudo **GSE60450** (Assay et al., 2014) sobre a glândula mamária de camundongos.
