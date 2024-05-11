# Chatbot Jurídico para Cientistas de Dados: Guia Prático sobre a LGPD

Este chatbot foi desenvolvido para auxiliar cientistas de dados a entenderem melhor a Lei Geral de Proteção de Dados (LGPD) e como ela se aplica aos seus projetos.

## Funcionalidades
- **Responda a perguntas sobre a LGPD** de forma clara e concisa.
- **Obtenha informações relevantes** sobre os aspectos da LGPD que impactam diretamente o trabalho de um cientista de dados.

## Como funciona
O chatbot utiliza dois poderosos modelos de Linguagem de Grande Porte (LLMs):

1. **Modelo de Embedding**: Um modelo de embedding foi treinado com textos abrangentes sobre a LGPD. Esse modelo transforma o texto em representações numéricas, chamadas embeddings, capturando o significado semântico do conteúdo. A partir da sua pergunta, o chatbot encontra a seção mais relevante da LGPD utilizando a similaridade entre os embeddings.
2. **Modelo Generativo Gemini Pro**: Responsável por gerar as respostas textuais. O Gemini Pro recebe a pergunta do usuário e o trecho mais relevante da LGPD encontrado pelo modelo de embedding e formula uma resposta completa, informativa e com linguagem jurídica adequada.

### A escolha dos dois modelos
A combinação do modelo de embedding com o Gemini Pro garante precisão na busca das informações relevantes sobre LGPD e permite respostas mais flexíveis, criativas e adaptadas ao contexto da pergunta do usuário.

## Público-alvo
Este chatbot é especialmente útil para cientistas de dados que podem ter dúvidas sobre quais dados podem ser tratados em seus projetos, considerando as diretrizes da LGPD.

## Observações
- Este chatbot é uma ferramenta educacional e não substitui a consultoria de um profissional da área jurídica.
- O modelo está em constante aprimoramento e pode ser enriquecido com mais dados e funcionalidades no futuro.

## OBS
O arquivo `lgpd_doc.json` encontra-se disponível para download na página inicial deste projeto. Desta forma, você poderá treinar seu próprio modelo com o `models/embedding-001`.

## Contribuições
Sinta-se à vontade para contribuir com o desenvolvimento do chatbot! Compartilhe suas sugestões, reporte problemas ou envie pull requests no repositório do GitHub. Juntos, podemos tornar este chatbot uma ferramenta ainda mais poderosa para a comunidade de cientistas de dados!
