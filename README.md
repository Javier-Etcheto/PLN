# Desafíos de PLN

Este repositorio contiene tres notebooks principales:

- `Desafio_1.ipynb`
- `Desafio_2.ipynb`
- `Desafio_3.ipynb`

Cada una corresponde a un desafío distinto. También se incluyen archivos auxiliares utilizados en el desarrollo.

## Desafío 1

Análisis de similaridad entre documentos vectorizados, clasificación con modelos Naive Bayes (Multinomial y ComplementNB), y estudio de similaridad entre palabras a partir de la transposición de la matriz documento-término.

## Desafío 2

Entrenamiento de embeddings propios con Gensim a partir del texto `Romeo_and_Juliet.txt`. Exploración de similitudes semánticas entre palabras, visualización y conclusiones.

## Desafío 3

Entrenamiento de modelos de lenguaje basados en RNN, LSTM y GRU usando el texto `A_journey_to_the_center_of_the_earth.txt`. Se utilizan estrategias de generación de texto (greedy, beam search determinístico y estocástico) y se analiza el efecto de la temperatura.

Se incluyen los siguientes archivos generados:

- Modelos entrenados: `model_rnn.keras`, `model_lstm.keras`, `model_gru.keras`
- Historias de perplejidad: `history_ppl_rnn.npy`, `history_ppl_lstm.npy`, `history_ppl_gru.npy`
- Visualización: `perplexity_vs_epoch.png`
