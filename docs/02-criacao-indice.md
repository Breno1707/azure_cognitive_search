
# 📚 Etapa 2: Criação do Índice Inteligente

## 🎯 Objetivo
Criar um índice no Azure Cognitive Search para estruturar os dados extraídos.

## 🛠️ Ferramentas Utilizadas
- Azure Cognitive Search
- Python SDK (azure-search-documents)
- Portal Azure

## 📐 Estrutura do Índice Criado
| Campo    | Tipo   | Chave Primária | Pesquisável | Ordenável | Filtrável |
|----------|--------|----------------|-------------|-----------|-----------|
| id       | String | ✅              | ❌          | ❌        | ❌        |
| titulo   | String | ❌              | ✅          | ✅        | ❌        |
| conteudo | String | ❌              | ✅          | ❌        | ❌        |
| entidades| Collection(String) | ❌ | ✅   | ❌        | ✅        |
| frases_chave | Collection(String) | ❌ | ✅ | ❌        | ✅        |

## 🔗 Passos Realizados
1. Definição dos Campos do Índice
2. Criação via SDK Python
3. Validação no Portal Azure

## 🖼️ Capturas de Tela
> ![Criação do índice](../assets/index-creation.png)
> ![Campos do índice](../assets/index-fields.png)

## ✅ Resultados
- Índice criado com sucesso.
- Campos preparados para filtros e facetas.

## 📝 Observações
- Analyzer pt.microsoft usado para português.
