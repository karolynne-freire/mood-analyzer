# 🎯 mood-analyzer — Análise de Sentimentos com IA

Este repositório demonstra uma aplicação simples e prática de IA utilizando a biblioteca `transformers` da Hugging Face. A proposta é analisar o sentimento de diferentes frases com base em um modelo de linguagem treinado.

## 📂 Estrutura

- `analise_sentimentos_IA.ipynb`: notebook com todo o código necessário para rodar a análise de sentimentos.
- `README.md`: explicação do projeto, processo e aprendizados.

## 🚀 Como utilizar

Você pode rodar o projeto diretamente no [Google Colab](https://colab.research.google.com/) em poucos passos:

1. Faça o download do arquivo `analise_sentimentos_IA.ipynb` aqui do repositório.
2. Acesse o [Colab](https://colab.research.google.com/) e clique em **"Upload"** para subir o notebook.
3. Execute as células na ordem para instalar as dependências, carregar o modelo e analisar as frases.
4. Você pode modificar ou adicionar novas frases na célula correspondente para testar diferentes resultados.

✅ **Não precisa instalar nada no seu computador. Basta usar o Colab e o arquivo já pronto do repositório!**

## 🔍 Exemplo de Análise

Uma das frases analisadas foi:

> "Hoje acordei com uma sensação boa, como se algo incrível fosse acontecer."

Resultado da IA:
[{'label': 'POSITIVE', 'score': 0.9991}]


## 💡 Insights
A IA conseguiu identificar corretamente sentimentos positivos e negativos com alta confiança.

Pequenas variações na estrutura da frase já são suficientes para alterar a percepção da IA.

Ferramentas como esta podem ser aplicadas em monitoramento de redes sociais, feedback de usuários, suporte emocional e mais.

## 📘 O que aprendi
Como utilizar a biblioteca transformers da Hugging Face.

Criar e executar pipelines de NLP (processamento de linguagem natural).

A importância de entender como a IA "interpreta" os sentimentos expressos em texto.

