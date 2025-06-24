# azure-ai-search-lab
Aplicar técnicas de organização e pesquisa de documentos por meio da ingestão de dados e indexação utilizando ferramentas de inteligência artificial. desenvolver uma compreensão sólida sobre como essas ferramentas podem ser utilizadas para minerar e extrair conhecimento de grandes volumes de informação.

---

# 🔍 Laboratório Azure AI Search — DIO

Este repositório contém os registros do desafio prático com **Azure AI Search**, com foco em ingestão de dados, criação de índices inteligentes e exploração prática de documentos organizados via IA.

---

## 🎯 Objetivo do Desafio

Explorar na prática como funcionam os três pilares do Azure AI Search:

1. Ingestão de dados
2. Indexação inteligente
3. Exploração e mineração de conhecimento

---

## 🛠️ Tecnologias Utilizadas

- [Azure AI Search (Portal)](https://portal.azure.com)
- Ferramenta de criação de índice (via portal ou REST API)
- Dataset (documentos .pdf, .txt ou JSON)
- GitHub para documentação técnica

---

## ✅ Etapas Realizadas

### 1. Ingestão de Dados

- Upload de arquivos PDF e textos para o Azure Blob Storage
- Criação de **data source** para o indexador da IA
- Configuração de campos customizados (ex: título, parágrafo, palavras-chave)

📸 *Captura:*
![Ingestão](./images/ingestion-step.png)

---

### 2. Indexação Inteligente

- Definição de esquema de indexação
- Uso de habilidades cognitivas (OCR, análise de linguagem, detecção de entidade)
- Criação e execução do indexador

📸 *Captura:*
![Index](./images/index-created.png)

---

### 3. Exploração de Dados

- Uso do **Search Explorer** no portal para testar buscas
- Interpretação dos resultados indexados
- Visualização de como as entidades e frases-chave foram extraídas automaticamente

---

## 💡 Insights e Aprendizados

- A IA Search é poderosa para organizar grandes volumes de documentos.
- Com poucos cliques, é possível transformar PDFs desorganizados em fontes consultáveis.
- O uso de habilidades cognitivas amplia as possibilidades: detecção de sentimentos, OCR, NER, etc.
- É possível integrar com APIs, web apps ou bots futuramente.

---

## 🗂️ Estrutura do Repositório

azure-ai-search-lab/
├── README.md
├── images/
│ └── index-created.png
└── notes/
└── insights.md

---

## ✍️ Autor

Desenvolvido por **Jules Martins**  
📧 julesem1970-tech | [github.com/Julesem1970-Tech](https://github.com/Julesem1970-Tech)

---

## 🔗 Links Úteis

- [Explore Azure AI Search (UI) — Microsoft Learning](https://learn.microsoft.com/en-us/training/modules/explore-azure-ai-search/)
- [Azure Cognitive Search Docs](https://learn.microsoft.com/en-us/azure/search/)
- [Guia Markdown GitHub](https://guides.github.com/features/mastering-markdown/)
