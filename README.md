# Detector de Origem de Conteúdo: IA ou Humano?

## 📒 Descrição
O projeto consiste em desenvolver uma metodologia que analise textos e determine se foram gerados por uma inteligência artificial (IA) ou escritos por um ser humano. A ideia central é entender as nuances entre os estilos de escrita de uma máquina e de uma pessoa, utilizando ferramentas de IA generativa e técnicas de aprendizado de máquina para aprimorar os resultados.

## 🤖 Tecnologias Utilizadas
- IAs Generativas: OpenAI ChatGPT (GPT-4), DALL-E, e outros modelos de linguagem baseados em redes neurais.
- Ferramentas de Análise de Texto: Python (bibliotecas como NLTK, SpaCy e Transformers).
- Plataformas de Desenvolvimento: Jupyter Notebook, Google Colab.
- Outras Ferramentas: VS Code para edição de código, GitHub para versionamento e Trello para organização do projeto.

## 🧐 Processo de Criação
1. Coleta de Dados: Inicialmente, foram coletados textos gerados por IAs e textos escritos por humanos. Essa coleta incluiu conteúdos de blogs, artigos e respostas geradas pelo ChatGPT.

2. Treinamento de Modelos: Um modelo de classificação foi treinado utilizando aprendizado supervisionado para diferenciar textos de IA e humanos. Utilizamos embeddings gerados pelo modelo BERT para representação vetorial dos textos.

3. Teste e Validação: Realizamos testes utilizando um conjunto de dados separado para avaliar a precisão do modelo. Ajustamos hiperparâmetros para melhorar os resultados.

4. Geração de Conteúdo: Para verificar a eficácia, textos falsos e reais foram criados e submetidos ao modelo para classificação.

## 🚀 Resultados
- O modelo alcançou 92% de acurácia na distinção entre textos gerados por IA e textos humanos.
- Os textos gerados por IA apresentaram padrões consistentes, como repetição de frases e estrutura linear, enquanto os textos humanos mostraram maior diversidade de estilo e criatividade.
- A implementação foi validada em vários cenários, como postagens de redes sociais e artigos acadêmicos.
