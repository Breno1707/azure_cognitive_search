
# 📥 Etapa 1: Ingestão de Conteúdo para IA

## 🎯 Objetivo
Nesta etapa, realizamos a ingestão dos documentos que serão indexados pelo Azure Cognitive Search. O processo inclui o upload dos arquivos para um armazenamento no Azure e a configuração da origem de dados no serviço de busca.

## 🛠️ Ferramentas Utilizadas
- Azure Blob Storage
- Azure Cognitive Search
- Skillsets de IA

## 📂 Estrutura dos Dados Ingeridos
- doc1.pdf - Introdução à Inteligência Artificial
- doc2.docx - Aplicações de IA no Setor da Saúde

## 🔗 Passos Realizados
1. Criação do Storage Account
2. Upload dos Documentos
3. Configuração da Fonte de Dados
4. Criação do Skillset de Enriquecimento
5. Execução do Indexador

## 🖼️ Capturas de Tela
> ![Upload dos documentos](../assets/blob-upload.png)
> ![Configuração da fonte](../assets/datasource-config.png)

## ✅ Resultados da Ingestão
- Documentos ingeridos: 2
- Campos extraídos: 5

## 📝 Observações
- Habilitar Cognitive Services para skillset.
