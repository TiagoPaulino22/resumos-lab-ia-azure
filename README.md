# 📖 Resumos dos Laboratórios Azure AI
### Este repositório contém o resumo das lições aprendidas sobre IA na Cloud Azure, durante o desenvolvimento dos labobarórios na DIO. 

## Sumário

[1. Resumo do laboratório 1: Análise de Sentimentos com Language Studio no Azure AI](#1.Resumo-do-laboratório-1-:-Análise-de-Sentimentos-com-Language-Studio-no-Azure-AI) </br>
[2. Resumo do laboratório 2: Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados](#2.Resumo-do-laboratório-2-:Azure-Cognitive-Search:-Utilizando-AI-Search-para-indexação-e-consulta-de-Dados)</br>
[3. Resumo do laboratório 3: Explorando os Recursos de IA Generativa com Copilot e OpenAI](#3.Resumo-do-laboratório-3-:Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI)</br>

### 1. Resumo do laboratório 1: Análise de Sentimentos com Language Studio no Azure AI

<ins>**Speech Studio**</ins>

Para a conversão de áudio em texto, foram seguidos os seguintes passos: 
1. Configurações – Criar novo recurso
2.  Conversão de fala em texto – Conversão de fala em texto em tempo real 
3.  Deixar marcado Reconheço que este aplicativo usa recurso servicodeocr...
4.  Escolher o idioma do arquivo de áudio que será carregado. 

Abaixo é mostrado o ambiente em que o aúdio pode ser carregado. 

![Imagem 1](/images/IA1.PNG)

<ins>**Language Studio**</ins>

Para a análise de sentimentos, foram seguidos os seguintes passos: 
1. Configuração de novo recurso
2.  Classify text - Analyze sentiment and opinions

Foi utilizada uma das amostras de texto disponíveis, o resultado é mostrado abaixo: 

![Imagem 1](/images/IA2.PNG)

![Imagem 1](/images/IA3.PNG)

### 🔎 Links úteis 
- [Explore Speech in Azure AI Foundry portal](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)
- [Analyze text in Azure AI Foundry portal](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)


### 2. Resumo do laboratório 2: Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

No laboratório foram configurados três recursos com o objetivo de fazer busca em documentos. 
Os passos realizados fora os seguintes: 

<ins>Criar grupo de recursos e detalhar instância no AI Search</ins>
1. Azure AI services – AI Search – Create a Search service
2. Change Pricing Tier – Selecionar o Basic

<ins>Criar um novo recurso de Inteligência artificiale detalhar a instância no AI Services</ins>
1. Create a resource – Create Azure AI services 
2. Pricing tier - Standard S0
3. Marcar a checkbox – By checking this box I acknowledge...

<ins>Criar um recurso de armazenamento</ins>
1. Azure Services – Storage accounts – Create
2. Configurar grupo de recursos e detalhes da instância
3. Performance – Standard
4. Redundancy – Locally-redundant Storage (LRS)

Configuração do Storage:
![Imagem 1](/images/IA4.PNG)

Essa configuração irá permitir adicionar o container. 
1. Data Storage – Containers – New container – Container (anonymous read access...)
2. Nome do container coffereviews
3. Carregar os arquivos para dentro do container em Upload

Utilizando o IA Search foi possível fazer pesquisas nos documentos armazenados utilizando filtros de localização e análise de sentimentos. 

### 3. Resumo do laboratório 3: Explorando os Recursos de IA Generativa com Copilot e OpenAI

