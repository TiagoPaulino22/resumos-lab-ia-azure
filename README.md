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

![Imagem 2](/images/IA2.PNG)

![Imagem 3](/images/IA3.PNG)

### 🔎 Links úteis 
- [Explore Speech in Azure AI Foundry portal](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)
- [Analyze text in Azure AI Foundry portal](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)


### 2. Resumo do laboratório 2: Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

No laboratório foram configurados três recursos com o objetivo de fazer buscas em documentos. 
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

Configuração do Storage. Essa configuração irá permitir adicionar o container.

![Imagem 4](/images/IA4.PNG)


<ins> Criar container e adicionar arquivos </ins>
1. Data Storage – Containers – New container – Container (anonymous read access...)
2. Nome do container coffereviews
3. Carregar os arquivos para dentro do container em Upload

Utilizando o IA Search foi possível fazer pesquisas nos documentos armazenados utilizando filtros de localização e análise de sentimentos. 

### 3. Resumo do laboratório 3: Explorando os Recursos de IA Generativa com Copilot e OpenAI

No início do laboratório foram apresentados os passos para gerar uma solução de IA responsável. 

![Imagem 5](/images/IA5.PNG)

Em seguida, foram explorados alguns recursos do Microssoft Copilot. 

Para geração de imagem, pedi para que fosse gerada uma imagem de um tigre e um leão brigando. O resultado é mostrado abaixo. 

![Imagem 6](/images/IA6.PNG)

Para geração de código, foi pedido que fosse gerado um código em Python de um jogo da velha. O resultado é mostrado a seguir. 

![Imagem 7](/images/IA7.PNG)

### 🔎 Links úteis 
- [Explore generative AI in Azure AI Foundry Portal](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html )
- [Apply content filters to prevent the output of harmful content](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/06-Explore-content-filters.html )
- [Prepare for an AI development project](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/01-Explore-ai-studio.html )

