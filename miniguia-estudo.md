Miniguia de Estudos: Engenharia de Prompts para IA Generativa

Objetivo deste Miniguia

Este material reúne os principais conhecimentos consolidados durante o estudo sobre Engenharia de Prompts.

O objetivo é servir como um guia rápido para futuras revisões, apresentando conceitos fundamentais, técnicas, exemplos e prompts reutilizáveis.

1. O que é Engenharia de Prompts?

Engenharia de Prompts pode ser entendida como o processo de elaborar, estruturar, testar e aprimorar instruções fornecidas a modelos de Inteligência Artificial.

O objetivo é comunicar com maior clareza o resultado esperado.

Em vez de apenas perguntar algo de forma genérica, uma pessoa pode fornecer informações adicionais para orientar a tarefa.

Por exemplo:

Prompt simples


Explique Python.


Prompt estruturado


Explique os fundamentos da linguagem Python para uma pessoa
que está começando a programar.

Organize a resposta em:

1. O que é Python;
2. Principais características;
3. Variáveis;
4. Condicionais;
5. Laços de repetição;
6. Um exemplo simples.

Utilize linguagem didática e exemplos curtos.


O segundo prompt apresenta mais informações sobre o objetivo e o formato esperado.



1. Por que os Prompts são Importantes?

A qualidade de uma resposta pode ser influenciada pela qualidade da instrução fornecida.

Um prompt pode informar:

* O que deve ser feito;
* Qual é o contexto;
* Quem utilizará a resposta;
* Qual nível de profundidade é necessário;
* Como a resposta deve ser apresentada;
* Quais limites devem ser respeitados.

Quanto maior a clareza sobre a tarefa, maior a possibilidade de reduzir ambiguidades.

3.Anatomia de um Prompt

Um prompt estruturado pode conter diferentes componentes.

3.1 Objetivo

Define o que deve ser realizado.

Exemplo:


Explique os conceitos fundamentais de Engenharia de Prompts.


3.2 Contexto

Fornece informações adicionais sobre a situação.

Exemplo:


Estou preparando um material de estudos sobre Inteligência Artificial.


3.3 Público

Define para quem a resposta será produzida.

Exemplo:


Considere que o leitor é iniciante no assunto.


3.4 Formato

Define como a resposta deve ser apresentada.

Exemplo:


Organize a resposta em tópicos e apresente uma tabela comparativa.


3.5 Restrições

Definem limites para a execução da tarefa.

Exemplo:


Baseie a resposta exclusivamente nas fontes fornecidas.
Caso não exista informação suficiente, informe essa limitação.


3.6 Exemplos

Podem demonstrar o tipo de resultado esperado.

Exemplo:


Apresente dois exemplos práticos após a explicação teórica.


4. Principais Técnicas

Zero-shot Prompting

A tarefa é solicitada sem fornecer exemplos específicos.

Exemplo


Classifique o seguinte texto como positivo, negativo ou neutro.


Característica

É uma abordagem direta e pode ser adequada para tarefas simples.



Few-shot Prompting

A instrução inclui exemplos para demonstrar o comportamento ou formato esperado.

Exemplo


Exemplo 1:
Entrada: Gostei muito do produto.
Saída: Positivo

Exemplo 2:
Entrada: Não gostei do atendimento.
Saída: Negativo

Agora classifique:
Entrada: O produto chegou dentro do prazo.


Característica

Os exemplos ajudam a demonstrar o padrão esperado.



Prompt Chaining

Uma tarefa complexa é dividida em múltiplas etapas.

Exemplo

Em vez de solicitar:


Analise este artigo e crie um plano completo de estudos.


A tarefa pode ser dividida em:


1. Identifique os principais conceitos.
2. Resuma cada conceito.
3. Identifique pré-requisitos.
4. Organize os conceitos por ordem de estudo.
5. Crie um plano de revisão.


Característica

A divisão pode facilitar a organização de tarefas complexas.

Role Prompting

Consiste em definir uma perspectiva ou função para orientar a resposta.

Exemplo


Atue como um tutor de programação e explique recursão
para uma pessoa iniciante.


Característica

Pode ajudar a orientar o estilo e a abordagem da explicação.

Output Formatting

Consiste em especificar o formato esperado.

Exemplos


Apresente em uma tabela.

Responda utilizando uma lista numerada.

Estruture como um checklist.


Característica

Ajuda a tornar o resultado mais adequado à finalidade desejada.

Refinamento Iterativo

Consiste em avaliar o resultado e modificar progressivamente o prompt.

Processo


Prompt inicial
      ↓
Resposta
      ↓
Análise
      ↓
Identificação de problemas
      ↓
Refinamento do prompt
      ↓
Nova resposta


Característica

Reconhece que o primeiro resultado pode ser utilizado como parte do processo de melhoria.



5. Processo de Criação de um Prompt

Um fluxo simples pode ser:

Passo 1 — Defina o objetivo

Pergunte:

> O que eu realmente quero obter?

Passo 2 — Adicione contexto

Pergunte:

> Quais informações são necessárias para compreender a tarefa?

Passo 3 — Defina o público

Pergunte:

> Para quem essa resposta será produzida?

Passo 4 — Escolha o formato

Pergunte:

> Como quero receber a resposta?

Passo 5 — Defina restrições

Pergunte:

> Existe algo que não deve ser feito?

Passo 6 — Avalie

Pergunte:

> A resposta realmente atende ao objetivo?

Passo 7 — Refine

Caso necessário:

* Adicione contexto;
* Solicite exemplos;
* Modifique o formato;
* Defina melhor o nível de profundidade;
* Divida tarefas complexas.

6. Prompt Vago x Prompt Estruturado

Prompt vago


Faça um resumo sobre Inteligência Artificial.


Problemas possíveis

* Qual tipo de Inteligência Artificial?
* Qual nível de profundidade?
* Para qual público?
* Qual tamanho?
* Quais tópicos são importantes?

Prompt estruturado


Crie um resumo introdutório sobre Inteligência Artificial Generativa
para estudantes iniciantes.

Explique:

1. O que é;
2. Como funciona de forma geral;
3. Principais aplicações;
4. Limitações;
5. Cuidados ao utilizar.

Utilize linguagem simples.

Organize em tópicos e limite o resumo a 500 palavras.


Melhoria

O segundo exemplo define:

* Tema;
* Público;
* Conteúdo;
* Formato;
* Limite.

7. Checklist de Prompt

Antes de enviar uma instrução, verifique:

* ()Meu objetivo está claro?
* ()Informei o contexto necessário?
* ()Defini o público?
* ()Indiquei o nível de profundidade?
* ()Especifiquei o formato esperado?
* ()Solicitei exemplos quando necessário?
* ()Defini restrições?
* ()Posso dividir a tarefa em etapas?
* ()Sei como avaliar a qualidade da resposta?

8. Glossário

| Termo                 | Definição                                                                                 |
| --------------------- | ----------------------------------------------------------------------------------------- |
| Prompt                | Instrução fornecida a um modelo de IA                                                     |
| Engenharia de Prompts | Processo de criar e aprimorar prompts                                                     |
| LLM                   | Modelo de linguagem de grande escala                                                      |
| Contexto              | Informação adicional utilizada para orientar uma tarefa                                   |
| Zero-shot             | Execução de uma tarefa sem exemplos específicos                                           |
| Few-shot              | Uso de exemplos para orientar o resultado                                                 |
| Prompt Chaining       | Divisão de uma tarefa em múltiplas etapas                                                 |
| Output                | Resultado produzido pelo modelo                                                           |
| Iteração              | Processo repetido de teste e melhoria                                                     |
| Refinamento           | Alteração do prompt para melhorar o resultado                                             |
| Restrição             | Limite definido para orientar uma tarefa                                                  |
| Alucinação            | Informação incorreta ou não fundamentada apresentada pelo modelo como se fosse verdadeira |

9. Prompts Reutilizáveis

9.1 Prompt para Resumo


Com base nas fontes fornecidas, resuma [TEMA].

Estruture a resposta em:

1. Definição;
2. Principais conceitos;
3. Pontos importantes;
4. Exemplo prático;
5. Resumo final.

Utilize linguagem adequada para [NÍVEL DO LEITOR].


9.2 Prompt para Explicação Didática


Explique [CONCEITO] para uma pessoa iniciante.

Siga esta estrutura:

1. Explicação simples;
2. Analogia;
3. Explicação técnica;
4. Exemplo prático;
5. Erros ou confusões comuns;
6. Resumo final.


9.3 Prompt para Comparação


Compare [CONCEITO A] e [CONCEITO B].

Apresente:

- Definição;
- Semelhanças;
- Diferenças;
- Vantagens;
- Limitações;
- Casos de uso;
- Exemplos.

Organize a resposta em uma tabela.

9.4 Prompt para Revisão


Crie 10 perguntas de revisão sobre [TEMA].

Organize as perguntas do nível básico ao avançado.

Não apresente as respostas imediatamente.

Após todas as perguntas, apresente um gabarito comentado.


9.5 Prompt para Criar Flashcards


Crie flashcards sobre [TEMA].

Utilize o formato:

Pergunta:
Resposta:

Crie [QUANTIDADE] flashcards e priorize os conceitos mais importantes.


9.6 Prompt para Identificar Lacunas


Com base nas respostas abaixo, avalie meu nível de compreensão
sobre [TEMA].

Identifique:

1. Conceitos que demonstro compreender;
2. Possíveis lacunas;
3. Erros conceituais;
4. Assuntos que devo revisar;
5. Próximo passo recomendado.

Não invente informações além das respostas fornecidas.


9.7 Prompt para Plano de Estudos


Crie um plano de estudos sobre [TEMA].

Meu nível atual é [NÍVEL].

Organize os conteúdos em ordem de aprendizado.

Para cada etapa, informe:

- O que estudar;
- Objetivo;
- Conceitos principais;
- Atividade prática;
- Forma de revisão.

10. Estratégia de Revisão

Uma possível estratégia para utilizar este miniguia é:

-Dia 1

Estudar os conceitos fundamentais.

-Dia 2

Revisar a anatomia de um prompt.

-Dia 3

Praticar técnicas como Zero-shot e Few-shot.

-Dia 4

Criar prompts utilizando diferentes formatos.

-Dia 5

Realizar comparações entre prompts simples e estruturados.

-Dia 6

Criar prompts para um tema diferente.

-Dia 7

Revisar o glossário e testar os prompts reutilizáveis.

Conclusão

A Engenharia de Prompts pode ser compreendida como uma habilidade de comunicação, experimentação e análise.

Não existe necessariamente uma única estrutura perfeita para todos os problemas.

A criação de prompts envolve compreender o objetivo, fornecer o contexto necessário, definir expectativas e analisar criticamente o resultado.

O processo pode ser resumido em:

> Definir → Instruir → Testar → Avaliar → Refinar → Aprender

O uso consciente de Inteligência Artificial exige participação ativa do usuário.

Uma resposta produzida por IA não deve ser aceita apenas porque parece convincente. É importante questionar, comparar informações, consultar fontes e avaliar se o resultado realmente atende ao objetivo.

> A melhor utilização da IA não acontece quando ela pensa no lugar do usuário, mas quando ajuda o usuário a aprender, explorar e tomar decisões com mais conhecimento.
