# 🤖 Analista de Sentimento Multimodal com IA

Este projeto foi desenvolvido como parte dos meus estudos no 2º período de Inteligência Artificial na **Faculdade FAMA (Anápolis/GO)**. O objetivo é demonstrar a aplicação prática de modelos multimodais em cenários reais de atendimento ao cliente e e-commerce.

## 🚀 Sobre o Projeto
O bot utiliza o conceito de **Multimodalidade**, integrando Processamento de Linguagem Natural (NLP) e Visão Computacional para uma análise 360º da experiência do cliente.

### Como funciona:
1. **Análise de Texto (NLP):** Utiliza um modelo baseado em **BERT** para identificar o sentimento do comentário do cliente (escala de 1 a 5 estrelas).
2. **Visão Computacional:** Utiliza o modelo **ViT (Vision Transformer)** do Google para identificar objetos ou danos em fotos enviadas pelo usuário.
3. **Lógica de Decisão:** O sistema cruza as duas informações. Se o cliente está insatisfeito e a imagem detecta um problema no produto/embalagem, o bot gera um alerta crítico para o suporte humano.

## 🛠️ Tecnologias e Ferramentas
- **Linguagem:** Python
- **Ambiente:** Google Colab
- **Bibliotecas:** Transformers (Hugging Face), PyTorch, Pillow
- **Modelos:** `nlptown/bert-base-multilingual-uncased-sentiment` e `google/vit-base-patch16-224`

## 👨‍💻 Autor
**Ryan Morais Lima** Estudante de Inteligência Artificial - Faculdade FAMA.  
Focado em desenvolver soluções inteligentes para otimização de processos e experiência do usuário.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16Rg2k6X9VdT-PjF7V8rbvLVHHqWT-j_T?usp=sharing)
