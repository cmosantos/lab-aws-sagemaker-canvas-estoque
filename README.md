# 🧠📊 Previsão de Estoque Inteligente na AWS com SageMaker Canvas  
**Bootcamp DIO + AWS – Machine Learning No-Code**

Este repositório contém minha solução para o desafio **“Previsão de Estoque Inteligente com AWS SageMaker Canvas”**, utilizando Machine Learning **no-code** para prever demanda de estoque e apoiar decisões estratégicas de negócio.

O projeto foi construído com base no repositório oficial:  
➡️ `digitalinnovationone/lab-aws-sagemaker-canvas-estoque`  

---

# 🌟 Visão Geral do Projeto

O objetivo deste lab é demonstrar como o **Amazon SageMaker Canvas** permite criar, treinar e analisar modelos de Machine Learning **sem escrever código**, utilizando datasets reais e processos totalmente guiados.

Este repositório documenta:

- A estrutura do projeto  
- Os datasets utilizados  
- O processo completo dentro do Canvas  
- Prints e evidências das etapas  
- Insights obtidos a partir das previsões  
- Conclusões finais  

---

# 📂 Estrutura do Repositório

lab-aws-sagemaker-canvas-estoque/
├── datasets/
│ ├── dataset-500-curso-sagemaker-canvas-dio.csv
│ ├── dataset-1000-com-preco-promocional-e-renovacao.csv
│ ├── dataset-1000-com-preco-variavel-e-renovacao.csv
│ └── estoque_supermercado.csv
│
├── docs/
│ ├── guia-uso-canvas.md
│ └── evidencias/
│ ├── 01-upload-dataset.png
│ ├── 02-config-modelo.png
│ ├── 03-treinamento.png
│ ├── 04-metricas.png
│ └── 05-previsoes.png
│
└── README.md


As imagens são **evidências do processo**, simuladas aqui como placeholders profissionais, podendo ser substituídas depois pelos prints reais do Canvas.

---

# 📁 Datasets Utilizados

A pasta `datasets/` contém quatro arquivos utilizados nos experimentos, simulando diferentes cenários de estoque e demanda:

- **dataset-500-curso-sagemaker-canvas-dio.csv**  
- **dataset-1000-com-preco-promocional-e-renovacao.csv**  
- **dataset-1000-com-preco-variavel-e-renovacao.csv**  
- **estoque_supermercado.csv** *(dataset principal usado no projeto)*

Esses datasets permitem comparar modelos e testar variações com promoções, renovação de estoque e flutuação de preço.

---

# ⚙️ Fluxo Completo no SageMaker Canvas

## **1️⃣ Selecionar Dataset**
- Upload via interface  
- Validação das colunas  
- Tratamento de dados básicos  

📸 *Evidência:*  
`docs/evidencias/01-upload-dataset.png`

---

## **2️⃣ Construir e Treinar o Modelo**
- Definição da variável alvo  
- Ajuste das variáveis de entrada  
- Treinamento automático  

📸 *Evidências:*  
`docs/evidencias/02-config-modelo.png`  
`docs/evidencias/03-treinamento.png`

---

## **3️⃣ Analisar Métricas**
- R²  
- Erros (MAE/MSE)  
- Feature Importance  

📸 *Evidência:*  
`docs/evidencias/04-metricas.png`

---

## **4️⃣ Gerar Previsões**
- Inserção de novos dados  
- Exportação do CSV  
- Leitura dos resultados  

📸 *Evidência:*  
`docs/evidencias/05-previsoes.png`

---

# 📈 Insights Gerados

- Identificação de produtos com risco de ruptura  
- Detecção de excesso de estoque  
- Relação direta entre preço/promos e demanda  
- Diferença de comportamento por categoria  

---

# 🧠 Aprendizados do Projeto

- ML no-code acelera o entendimento de processos de IA  
- Canvas fornece resultados claros para tomada de decisão  
- Usar múltiplos datasets ajuda a comparar cenários  
- Visualizar métricas facilita interpretação  

---

# 🚀 Como Executar o Projeto

1. Clone este repositório:
```bash
git clone https://github.com/cmosantos/lab-aws-sagemaker-canvas-estoque
cd lab-aws-sagemaker-canvas-estoque

