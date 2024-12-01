# **🔍 Análise de Documentos Anti-fraude com AzureAI**

Uma solução baseada em inteligência artificial para analisar imagens de documentos e identificar possíveis indícios de fraude. Utilizando o poder do **Azure OpenAI** e a biblioteca **Azure AI Document Intelligence**, este projeto automatiza a análise de arquivos de imagem, permitindo maior eficiência e precisão na detecção de anomalias.

---

## **📝 Descrição**

O **Análise de Documentos Anti-fraude com AzureAI** é uma solução desenvolvida para processar imagens de documentos em formatos **PNG**, **JPG** e **JPEG**.  
O sistema usa IA para identificar padrões suspeitos, anomalias e inconsistências que possam ser indicativos de fraude, exibindo os resultados em uma interface interativa e amigável desenvolvida com **Streamlit**.

Uma futura atualização incluirá suporte para análise de documentos no formato PDF.

---

## **💻 Tecnologias Utilizadas**

As seguintes tecnologias e bibliotecas foram utilizadas no desenvolvimento deste projeto:

- **Linguagem:** Python 3.x
- **APIs e Serviços:**
  - **Azure AI Document Intelligence** (análise de documentos em imagens)
  - **Azure OpenAI** (interpretação avançada de linguagem)
  - **Azure Blob Storage** (armazenamento de arquivos de imagem)
- **Bibliotecas**:
  - `azure-ai-documentintelligence` (para análise de imagens de documentos)
  - `azure.core` (para integração com os serviços da Azure)
  - `streamlit` (para criação da interface web interativa)
  - `azure-storage-blob` (para gerenciar arquivos no Azure Blob Storage)
  - `python-dotenv` (para gerenciamento de variáveis de ambiente)

---

## **⚙️ Processo de Criação**

1. **Planejamento**:
   - Definição do fluxo de análise para arquivos de imagem.
   - Seleção dos serviços Azure apropriados para OCR e interpretação avançada.

2. **Desenvolvimento**:
   - **Processamento de Imagens**:
     - Implementação de rotinas para processar e analisar imagens usando o Azure AI Document Intelligence.
   - **Análise Semântica**:
     - Integração com o Azure OpenAI para identificar padrões linguísticos e potenciais fraudes.
   - **Interface Interativa**:
     - Criação de uma aplicação com Streamlit para upload de imagens e exibição dos resultados de análise.
   - **Armazenamento**:
     - Configuração do Azure Blob Storage para armazenar e recuperar imagens enviadas.

3. **Testes**:
   - Testes em imagens de diferentes qualidades e formatos.
   - Validação de resultados para identificar inconsistências com alta precisão.

---

## **📊 Resultados**

- **🚀 Agilidade e Eficiência**: 
  - Processamento automatizado de imagens de documentos, reduzindo o tempo de análise.
- **🎯 Alta Precisão**:
  - Identificação confiável de padrões suspeitos em textos extraídos de imagens.
- **📈 Escalabilidade**:
  - Preparado para lidar com volumes crescentes de documentos em ambientes corporativos.

---

## **🤔 Reflexão**

Este projeto demonstrou o potencial das ferramentas Azure na análise de documentos anti-fraude. Durante o desenvolvimento, destacaram-se:

- **Pontos Positivos**:
  - A integração com Azure AI Document Intelligence proporcionou OCR robusto para imagens.
  - A aplicação Streamlit ofereceu uma interface simples e funcional para os usuários.
- **Desafios**:
  - Garantir precisão em imagens de baixa qualidade.
  - Ajustar prompts para uma análise contextualizada e relevante.

**Futuras Implementações**:
- Suporte a arquivos PDF utilizando `pdfplumber` ou serviços adicionais do Azure.
- Alertas automáticos para casos suspeitos.
- Expansão para idiomas adicionais, além do Português do Brasil.

---
