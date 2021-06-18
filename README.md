# Desafio Backend - Chatbot
Nesse desafio você contruirá um chatbot.

Contexto
===
Para um chatbot funcionar é importante entender como ele reconhece informações e como parametrizá-lo e para isso existem dois conceitos muito importantes:
* _Expressões_: São exemplos de textos utilizados para treinar um chatbot e "ensiná-lo" como detectar diferentes intenções dos usuários.
* _Intenção_: É a classificação que o bot irá fazer para as mensagens recebidas. Á partir da classificação é decidido como o bot deve responder. Cada intenção deve ter uma ou mais expressões.
* _Resposta_: Como o bot deve responder cada intenção identificada para os inputs dos usuários. Cada intenção tem uma resposta associada.

O desafio é contruir uma solução que permita criar o modelo de cognição do chatbot, cadastrando intenções e expressões para o treinamento do bot e as respostas para cada intenção.

Pode ser utilizado algum provedor de cognição à sua escolha ([IBM Watson](https://cloud.ibm.com/apidocs/assistant/assistant-v1), [MS LUIS](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c2f), [Dialogflow](https://cloud.google.com/dialogflow/es/docs/reference/rest/v2-overview), etc) ou implementar um algoritmo próprio para classificação.

As respostas do bot para cada intenção devem ser mantidas pela própria solução em um banco de dados.

Deve expor uma API REST que receberá o input do usuário e retornar a resposta correspondente ao treinamento realizado (Mensagem de resposta da inteção na qual a mensagem foi classificada) de acordo com que está cadastrado no banco de dados.


Restrições
===
1. A solução deve ser escrita em Go, Python ou .Net (5 ou Core 3.1).
2. Pode ser utilizado como banco de dados o MongoDB ou PostgreSQL.
3. O projeto deve ter um README.md com todas as instruções sobre como executar e testar a solução.
4. O código deve ser escrito em inglês.


Recomendações
====
* Escreva testes
* Utilize princípios [SOLID](https://en.wikipedia.org/wiki/SOLID)
* Utilize boas práticas de programação
* Utilize boas práticas de git (mensagens de commit claras e em inglês)
* Atenção à estrutura de dados
* Atenção à detalhes de API REST


Avaliação
====
1. A entrega do desafio deve ser feita por email, contendo um link para o repositório no github
2. Iremos avaliar a arquitetura da solução, qualidade de código, entendimento das regras de negócio, capricho com o desafio e o quão preparado o seu código estaria para ser rodado em produção.
3. Depois de avaliado o desafio, te chamaremos para apresentá-lo e discutir sobre as decisões que você tomou.
4. O prazo de entrega do desafio é de 1 semana, mas caso precise de mais tempo é só nos avisar.
