# Aprendizagem de Máquina II | Fatec Jundiaí — 6º semestre (2026/2)

Repositório acadêmico de **Aprendizagem de Máquina II**, disciplina do curso de **Ciência de Dados** da **Fatec Jundiaí**, cursada no 6º semestre de 2026. Organização por encontros semanais, normalmente às **quintas-feiras**.

## Notebooks publicados

| Data de referência | Conteúdo e notebook |
| --- | --- |
| 13/08/2026 | [Classificação multirrótulo com Random Forest](aulas/2026-08-13/classificacao-multirrotulo-random-forest.ipynb) |
| 20/08/2026 | [AdaBoost e classificação de risco](aulas/2026-08-20/adaboost-e-classificacao-de-risco.ipynb) |
| 27/08/2026 | [Avaliação de classificadores e validação cruzada](aulas/2026-08-27/avaliacao-de-classificadores-e-validacao-cruzada.ipynb) |
| 03/09/2026 | [Regressão logística vs. MLP em dados não lineares](aulas/2026-09-03/classificacao-nao-linear-regressao-logistica-mlp.ipynb) |
| 03/09/2026 | [Rede RBF: implementação e comparação (adaptação da aula)](aulas/2026-09-03/rede-rbf-implementacao-e-comparacao.ipynb) |
| 10/09/2026 | [Pipelines, GridSearchCV e comparação de modelos](aulas/2026-09-10/pipelines-gridsearch-e-comparacao-de-modelos.ipynb) |
| 17/09/2026 | [Atividade A1: seleção de modelos no Breast Cancer Wisconsin](aulas/2026-09-17/atividade-a1-selecao-de-modelos-breast-cancer.ipynb) |
| 08/10/2026 | [RBF e classificação de círculos concêntricos](aulas/2026-10-08/rede-rbf-classificacao-circulos-concentricos.ipynb) |
| 08/10/2026 | [Rede RBF com Keras/TensorFlow (data de referência)](aulas/2026-10-08/rede-rbf-keras-tensorflow.ipynb) |
| 29/10/2026 | [Overfitting, Dropout e callbacks](aulas/2026-10-29/redes-neurais-overfitting-dropout-callbacks.ipynb) |
| 29/10/2026 | [Versão comentada: Overfitting, Dropout e callbacks](aulas/2026-10-29/redes-neurais-overfitting-dropout-callbacks-comentado.ipynb) |
| 05/11/2026 | [Classificação MNIST: MLP vs. CNN](aulas/2026-11-05/classificacao-mnist-mlp-cnn.ipynb) |

**Total:** 12 notebooks organizados em 9 datas de referência.

## Conteúdos e tecnologias

- **Aprendizagem supervisionada:** classificação, comparação de algoritmos e métricas.
- **Preparação e avaliação:** padronização, divisão treino/teste, validação cruzada, `Pipeline` e `GridSearchCV`.
- **Ensembles:** Random Forest e AdaBoost.
- **Redes neurais:** MLP, RBF, Dropout, callbacks, redes convolucionais e classificação de imagens MNIST.
- **Bibliotecas:** Python, NumPy, pandas, Matplotlib, scikit-learn, TensorFlow/Keras; algumas aulas também utilizam Seaborn.

## Convenções de organização

- Pastas: `aulas/AAAA-MM-DD/`.
- Arquivos: nomes descritivos em minúsculas, sem acentos, separados por hífens.
- Datas: identificadas no título ou no próprio notebook. **O notebook RBF Keras/TensorFlow foi associado a 08/10 por proximidade temática e data de modificação, não por data expressa no título.** A versão RBF de 03/09 declara ser uma adaptação dessa aula.
- Variantes comentadas permanecem identificadas como tais; não são tratadas como projetos distintos.

## Como executar

Abra o arquivo `.ipynb` no [Google Colab](https://colab.research.google.com/) ou em um Jupyter Notebook e instale as bibliotecas importadas no próprio material. Os notebooks foram publicados **sem saídas salvas de execução**, para reduzir tamanho e evitar compartilhar resultados acidentais.

> **Estado de revisão:** a estrutura, os títulos e os trechos principais do código foram inspecionados; **não foi realizada execução integral nem validação automática de todos os notebooks**. Alguns materiais acadêmicos podem conter erros ou células incompletas e são preservados como registro de estudo.

## Correções aplicadas e pontos para revisão

- **13/08 (corrigido):** referência a `matriz_rotulos` substituída pela matriz efetivamente criada, `y_binarizado`. Removida também uma mensagem de depuração desnecessária.
- **03/09 (revisado):** títulos, comentários e textos de saída padronizados, preservando os experimentos. A exibição da acurácia foi ajustada para percentual.
- **08/10 (corrigido):** a segunda classe do gráfico agora usa a mesma máscara de classe 1 nos dois eixos.
- **17/09:** existe também um rascunho menor da A1 no Drive; foi priorizada a versão mais completa.
- **29/10:** versão original e comentada preservadas para comparação.

## Autoria e uso

Organização dos estudos: Ariel Ladislau Reises. Conteúdo acadêmico para fins educacionais e de portfólio. Referências, materiais fornecidos em aula e contribuições de colegas devem manter os devidos créditos quando aplicável.

**Fonte dos materiais:** notebooks originais no Google Drive / Google Colab. Os arquivos de origem não foram modificados.
