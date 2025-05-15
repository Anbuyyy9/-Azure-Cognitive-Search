# ☁️ Azure Cognitive Search - Projeto Fourth Coffee

Este projeto demonstra como configurar e utilizar o **Azure Cognitive Search** para extrair insights valiosos a partir de documentos armazenados no Azure Blob Storage, utilizando habilidades cognitivas e recursos de IA.

---

## 📌 Objetivo

Configurar uma solução de **mineração de conhecimento** para a empresa fictícia **Fourth Coffee**, permitindo a análise de documentos e extração de informações por meio de frases-chave, enriquecimento cognitivo e consultas avançadas.

---

## 🛠️ Etapas do Projeto

### 1. 🔧 Criação de Recursos no Azure

- Acesse o [Portal do Azure](https://portal.azure.com)
- Crie um recurso **Azure AI Search** com as configurações desejadas
- Verifique e finalize a criação do recurso

### 2. 🤖 Provisionamento de Serviços de IA

- Crie um recurso de **Serviços de IA do Azure** no mesmo grupo de recursos e região do AI Search
- Conclua o provisionamento

### 3. 💾 Configuração da Conta de Armazenamento

- Crie uma **conta de armazenamento** com acesso anônimo de blobs habilitado (leitura pública)
- Crie um contêiner e realize o **upload dos documentos** que serão indexados

### 4. 🔍 Indexação dos Documentos

- Acesse o recurso do Azure AI Search
- Clique em **"Importar dados"**
- Conecte-se ao Blob Storage e forneça os dados de conexão
- Adicione **Habilidades Cognitivas** (OCR, frases-chave, etc.)
- Especifique os campos enriquecidos e configure o **armazenamento de conhecimento**
- Personalize o índice de destino e **crie um indexador**

### 5. ✅ Verificação da Indexação

- Verifique o **status do indexador** e confirme a indexação bem-sucedida

### 6. 🔎 Consulta ao Índice

- Acesse o **Search Explorer**
- Escreva e teste consultas sobre os dados indexados
- Visualize os resultados retornados pela busca

### 7. 📦 Revisão do Armazenamento de Conhecimento

- Acesse a **conta de armazenamento**
- Explore os contêineres contendo dados enriquecidos: projeções, tabelas, frases-chave, etc.

### 8. 🧠 Análise das Frases-chave

- Examine as **frases-chave extraídas**
- Avalie os dados para obter insights relevantes sobre os conteúdos dos documentos

### 9. 📊 Exploração dos Resultados

- Analise os resultados e aplique os insights para:
  - Tomada de decisões
  - Otimização de atendimento ao cliente
  - Aprimoramento da solução de mineração de conhecimento

---

## 💡 Observações

> Certifique-se de seguir cada etapa com atenção para garantir que a solução seja corretamente configurada e forneça os insights necessários sobre as experiências dos clientes da **Fourth Coffee**.

---

## 🧰 Tecnologias Utilizadas

- Azure AI Search
- Azure Cognitive Services
- Azure Blob Storage
- Search Explorer

---
