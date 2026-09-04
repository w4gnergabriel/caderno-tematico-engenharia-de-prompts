Engenharia de Prompts: Testes, Variações e Cicatrizes

Objetivo

Esta seção documenta o processo de experimentação realizado durante o estudo sobre Engenharia de Prompts.

O objetivo não foi apenas obter respostas, mas observar como diferentes formas de escrever uma instrução podem influenciar o resultado produzido.

Cada experimento foi estruturado seguindo a lógica:

Prompt → Resultado observado → Problema → Refinamento → Aprendizado


Experimento 01 — Prompt Genérico

Prompt utilizado


Explique o que é Engenharia de Prompts.


Resultado observado

-A resposta tende a apresentar uma definição geral sobre o conceito.

Problema encontrado

O prompt não informa:

* Para quem a explicação será produzida;
* Qual nível de profundidade é esperado;
* Como a resposta deve ser organizada;
* Se exemplos devem ser utilizados.

Isso pode resultar em respostas corretas, mas pouco adequadas ao objetivo específico de estudo.

Aprendizado

Uma pergunta curta pode ser suficiente para obter uma resposta, mas não necessariamente garante que o resultado seja adequado à necessidade do usuário.

Experimento 02 — Adicionando o Público

Prompt utilizado


Explique o que é Engenharia de Prompts para uma pessoa que está
começando a estudar Inteligência Artificial Generativa.

Utilize linguagem simples e exemplos práticos.


Resultado observado

-A resposta tende a se tornar mais didática.

Melhoria observada

A definição do público ajuda a orientar:

* A complexidade da linguagem;
* O nível de profundidade;
* O tipo de exemplo utilizado.

Aprendizado

Definir para quem a resposta será produzida é uma estratégia importante para reduzir diferenças entre o resultado esperado e o resultado obtido.

Experimento 03 — Definindo o Objetivo

Prompt utilizado


Estou criando um material de estudos sobre Engenharia de Prompts.

Explique o conceito de forma didática para um iniciante.
Meu objetivo é compreender os fundamentos antes de estudar técnicas
mais avançadas.


Resultado observado

-A inclusão do objetivo fornece mais contexto sobre a finalidade da resposta.

Aprendizado

Além de informar o tema, explicar o motivo pelo qual a informação está sendo solicitada pode ajudar a orientar a resposta.

Experimento 04 — Definindo a Estrutura

Prompt utilizado


Explique Engenharia de Prompts para um iniciante.

Estruture a resposta nas seguintes seções:

1. Definição;
2. Importância;
3. Principais elementos;
4. Exemplo de prompt simples;
5. Exemplo de prompt melhorado;
6. Principais aprendizados.

Utilize linguagem objetiva.


Resultado observado

-A resposta tende a apresentar maior organização.

Problema resolvido

Em respostas anteriores, a organização do conteúdo não era necessariamente adequada para utilização como material de estudo.

Aprendizado

Definir o formato esperado é uma forma eficiente de orientar a apresentação da informação.

Experimento 05 — Incluindo Restrições

Prompt utilizado

text
Com base exclusivamente nas fontes disponíveis, explique o conceito
de Engenharia de Prompts.

Não invente informações que não estejam presentes nas fontes.

Caso não exista informação suficiente para responder, informe
explicitamente essa limitação.

Organize a resposta em tópicos.


Resultado observado

-A resposta passa a possuir uma orientação mais clara em relação aos limites da tarefa.

Aprendizado

Restrições ajudam a definir não apenas o que deve ser feito, mas também os limites que devem ser respeitados.

Experimento 06 — Solicitando Comparação

Prompt utilizado


Compare os conceitos de Zero-shot Prompting e Few-shot Prompting.

Apresente:

- Definição;
- Principais diferenças;
- Quando utilizar;
- Vantagens;
- Limitações;
- Um exemplo de cada técnica.

Apresente a resposta em formato de tabela.


Resultado observado

A definição explícita dos critérios de comparação facilita a obtenção de uma resposta estruturada.

Aprendizado

Em tarefas comparativas, é importante informar quais aspectos devem ser utilizados como critérios.

Experimento 07 — Refinamento Iterativo

Primeira versão

-Explique Few-shot Prompting.


Problema

A resposta pode não possuir o nível de detalhamento necessário.



Segunda versão

-Explique Few-shot Prompting para um iniciante em Inteligência Artificial.

Utilize um exemplo simples.


Melhoria

A solicitação passa a considerar o nível de conhecimento do leitor.



Terceira versão

-Explique Few-shot Prompting para um iniciante em Inteligência Artificial.

Estruture a resposta em:

1. Definição;
2. Como funciona;
3. Quando utilizar;
4. Vantagens;
5. Limitações;
6. Exemplo prático.

Ao final, apresente um resumo em três linhas.


Resultado

A terceira versão apresenta instruções mais específicas sobre conteúdo e formato.

Aprendizado

O refinamento de um prompt pode ser realizado progressivamente.

Não é necessário encontrar a versão perfeita na primeira tentativa.

Cicatrizes do Processo

Durante a experimentação, alguns problemas foram identificados.

Cicatriz 01 — Resposta muito genérica

Problema

A solicitação possuía poucas informações sobre o resultado esperado.

Solução

Adicionar:

* Contexto;
* Público;
* Objetivo.

Aprendizado

A IA precisa compreender não apenas sobre o que responder, mas também **por que e para quem responder.

Cicatriz 02 — Resposta sem organização

Problema

A resposta apresentava informações relevantes, porém em uma estrutura pouco adequada para estudo.

Solução

Definir explicitamente o formato:

* Tópicos;
* Tabela;
* Passo a passo;
* Seções;
* Checklist.

Aprendizado

O formato é parte importante da instrução.

Cicatriz 03 — Nível de profundidade inadequado

Problema

Algumas respostas eram simples demais ou complexas demais.

Solução

Informar:

* O nível do leitor;
* O conhecimento prévio;
* A profundidade desejada.

Aprendizado

O mesmo tema pode precisar de explicações completamente diferentes dependendo do público.

Cicatriz 04 — Falta de exemplos

Problema

Uma definição teórica nem sempre era suficiente para compreender o conceito.

 Solução

Solicitar explicitamente:

Apresente pelo menos um exemplo prático após a explicação.


Aprendizado

Se um elemento é importante para o resultado, ele deve ser solicitado.

Cicatriz 05 — Necessidade de validação

Problema

Uma resposta bem escrita não é automaticamente uma resposta correta.

Solução

Comparar as informações produzidas com as fontes selecionadas.

Aprendizado

A IA deve apoiar o processo de aprendizagem, mas não substituir a análise crítica.

Resumo dos Experimentos

| Experimento | Estratégia              | Problema identificado            | Aprendizado                     |
| ----------- | ----------------------- | -------------------------------- | ------------------------------- |
| 01          | Prompt genérico         | Pouco controle sobre o resultado | Clareza é necessária            |
| 02          | Público definido        | Linguagem inadequada             | Conhecer o leitor ajuda         |
| 03          | Objetivo definido       | Falta de contexto                | A finalidade orienta a resposta |
| 04          | Formato definido        | Falta de organização             | Estrutura melhora a utilidade   |
| 05          | Restrições              | Possíveis desvios                | Limites orientam a tarefa       |
| 06          | Critérios de comparação | Comparação superficial           | Critérios devem ser explícitos  |
| 07          | Refinamento             | Resultado inicial insuficiente   | Iteração melhora o prompt       |

Modelo Reutilizável de Prompt

Um modelo geral que pode ser utilizado em futuros estudos é:


CONTEXTO:
Estou estudando [TEMA].

OBJETIVO:
Quero compreender [CONCEITO OU PROBLEMA].

PÚBLICO:
Considere que possuo nível [INICIANTE / INTERMEDIÁRIO / AVANÇADO].

INSTRUÇÕES:
Explique o conteúdo de forma [DIDÁTICA / TÉCNICA / OBJETIVA].

ESTRUTURA:
Organize a resposta em:
1. Definição;
2. Principais conceitos;
3. Funcionamento;
4. Exemplo;
5. Limitações;
6. Resumo.

RESTRIÇÕES:
Baseie a resposta nas fontes fornecidas.
Caso não existam informações suficientes, informe essa limitação.


Conclusão dos Experimentos

A principal conclusão obtida durante os testes é que a criação de prompts deve ser tratada como um processo de comunicação e refinamento.

Um resultado inicial pode ser utilizado para identificar:

* Informações ausentes;
* Ambiguidades;
* Falhas de estrutura;
* Nível de profundidade inadequado.

Esses problemas podem orientar a próxima versão do prompt.

> Um prompt não precisa ser perfeito na primeira tentativa. A melhoria faz parte do processo.
