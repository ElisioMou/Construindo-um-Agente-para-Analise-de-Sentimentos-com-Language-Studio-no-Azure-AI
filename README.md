# Construindo-um-Agente-para-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI
Laboratório: Bootcamp DIO/Randstad - Análise de Dados

## 📋 Descrição:

Este laboratório prático teve o intuito de explorar as capacidades das ferramentas do Azure AI Language Studio, no qual foi possível analisar o nível de sentimentos em textos, para isso utilizando o processamento de linguagem natural (NLP).

## 🎯 Objetivos:
 - Aplicar os conceitos de NLP na prática usando as ferramentas do Azure AI na nuvem;
 - Documentar processos técnicos de forma clara e estruturada;
 - Desenvolver soluções baseadas em inteligência artificial para análise de texto;
 - Entregar um repositório contendo anotações e insights adquiridos para apoio de estudos e futuras implementações. 

## ⚙️ Etapas:
 1. Implantação de uma conta de armazenamento: local centralizado e seguro na nuvem (contêiner) onde é armazenado e gerenciado os diferentes tipos de dados.
    <img src="https://github.com/user-attachments/assets/e65f0ea3-ea4a-40eb-a702-b4339efcb6fa" height="500" width="800">
 2. Criação de um novo recurso Language Service: adiciona capacidades de inteligência artificial para processamento de linguagem natural (PLN). A PNL permite criar soluções que extraem significado semântico de texto ou fala, formulando respostas significativas em linguagem natural.
    
    <img src="https://github.com/user-attachments/assets/a40d12de-5c21-451b-a5de-d50f598f24d9" height="500" width="800">
    
    <img src="https://github.com/user-attachments/assets/345b7aa8-77ba-48e1-9f1d-d38050757793" height="500" width="800">
    
    <img src="https://github.com/user-attachments/assets/e34862cb-f7b8-4a46-bcbe-22db7b804fc3" height="500" width="800">
        
 3. Após o deploy, implantação do recurso de linguagem foi realizada com sucesso.
 
    <img src="https://github.com/user-attachments/assets/2bbc9518-6336-4395-8ec4-0825ea780a17" height="500" width="800">

 4. Acesso ao Language Studio e seleção de um recurso do Azure, do tipo "Idioma": é possível realizar a análise de texto e recursos de PNL, incluindo a identificação de frases-chave e classificação do texto com base no sentimento.

     <img src="https://github.com/user-attachments/assets/5fe8f863-c157-41e0-af16-842924b01cbd" height="500" width="800"> 
  
 5. Para realização da análise foi usado o serviço "Analisar sentimentos e as minhas opiniões", na aba "Classificar texto".
  
    <img src="https://github.com/user-attachments/assets/755dd8f9-dff3-4462-8498-f52fd46a101e" height="500" width="800">
   
 6. Upload de um arquivo .txt contendo algumas sentenças em português-br.
  
    <img src="https://github.com/user-attachments/assets/34235a03-aa00-4be6-90a1-250d33f9dfec" height="500" width="800">
  
## 📊 Análises:
 - Após executar a "Análise de sentimentos e opiniões" retornou os resultados abaixo. Neles é possível conferir os rótulos de sentimento (negativo, neutro e positivo), as pontuações de confiança na sentença e o nível do documento. Também, pode-se alternar para o formato JSON onde é possível ver os resultados através de campos chaves e valores.
 
   <img src="https://github.com/user-attachments/assets/1695df7b-e0ac-402b-bfd1-135c1652cd17" height="500" width="800">
   
   <img src="https://github.com/user-attachments/assets/fd3f1b00-a33f-4190-9c8c-975511f1f484" height="500" width="800">

## 💡 Conclusões:
 - O documento apresenta predomínio de sentimento negativo (72%), indicando que a maior parte transmite insatisfação, críticas ou emocionalidade adversa. Isso requer uma atenção o quanto antes para identificar as causas-raiz.
 - O sentimento do documento é classificado como misto (mixed), com baixa confiança (25%), indicando que há contradições não capturadas pela análise superficial. Isso sugere a importância de analisar as sentenças individualmente.
 - A frase "Então quem é o invencível?" possui 95% de negatividade, sugerindo um tom de desafio, ironia ou frustração. Isso reforça a necessidade de se investigar o contexto por trás dessa expressão.
 - A combinação de alta negatividade + baixa neutralidade (3%) sugere que o conteúdo é emocionalmente carregado e potencialmente polarizado. Então, é preciso usar estratégias de comunicação empática ou revisar processos que podem ser úteis para mitigar os conflitos.
