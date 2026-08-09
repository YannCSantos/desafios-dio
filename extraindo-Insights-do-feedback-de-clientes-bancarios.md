## Desafio
Extrair insights de feedbacks de clientes bancários com apoio de IA, usando contexto, critérios de análise e cuidados com dados sensíveis.
#### 🧱 Passo 1: Defina a intenção
Nesta etapa, você vai descrever o que a IA deve produzir, para quem e com qual finalidade.
Antes de escrever o prompt, responda: que tipo de feedback será analisado? Quem vai usar o resultado? Qual decisão esse resultado deve apoiar?
Pense em uma entrega simples, como uma lista de temas recorrentes, um resumo executivo ou uma tabela com problemas e ações sugeridas.
#### 🧱 Passo 2: Adicione Contexto e Restrições
Nesta etapa, você vai incluir informações de apoio, limites e cuidados para orientar melhor a resposta da IA.
Agora complemente sua intenção com contexto. Quais dados estarão disponíveis? Quais colunas ou campos existem? Que cuidados a IA deve ter ao lidar com feedbacks bancários?
Inclua também o que a IA deve evitar, como inventar dados, expor informações pessoais, ignorar comentários negativos ou tirar conclusões sem evidência.
#### 🧱 Passo 3: Una as Peças e Refine
Nesta etapa, você vai juntar intenção, contexto, critérios e restrições em um único prompt final.
Reúna o que você escreveu nos passos anteriores e transforme tudo em um comando claro para a IA. O prompt final deve dizer o papel da IA, o objetivo, os dados que serão analisados, o formato da resposta e os cuidados esperados.
Depois de montar o prompt, revise: a tarefa está clara? O formato da resposta foi definido? A IA sabe o que evitar?
### Prompt
Atue como analista de dados com experiência em relacionamento CRM.
Sua tarefa é analisar feedbacks de clientes sobre os serviços de pagamento e atendimento / suportes para identificar oportunidades de melhorias, gargalos em processo e, então, sugerir mudanças.  
A análise será usada por uma equipe de experiência do cliente para priorizar melhorias nos canais digitais e reduzir atritos no atendimento.    
Os dados que devem ser considerados para análise são: 
- Data da avaliação; Origem do Canal de Atendimento (app, agência, telefone, chat);
- O texto da avaliação;
- A categoria da avaliação (reclamação, sugestão, elogio);
- Serviço avaliado;
- Nota de satisfação.  

Instruções de análise:
1. Classifique os feedbacks por Serviço avaliado, categoria de avaliação e serviço avaliado.
2. Identifique os principais padrões, problemas, elogios e oportunidades.
3. Aponte evidências nos dados fornecidos.
4. Sugira ações práticas para equipe de desenvolvimento para identificação de problemas críticos ou recorrentes; E para equipe de suporte para sugestão de processos de atendimento que melhorem a experiência dos clientes.  
Entregue um resumo executivo com até 5 linhas, uma tabela com serviço avaliado, evidência e ação sugerida, além de uma lista final com as 3 prioridades mais importantes.  

Restrições:
- Use apenas os dados fornecidos.
- Não invente números, causas ou conclusões.
- Não exponha dados pessoais ou sensíveis.
- Informe limitações quando os dados não forem suficientes.
- Use linguagem simples, objetiva e orientada para tomada de decisão.
