# Pontos importantes sobre SQL e NoSQL

- Contexto geral sobre o uso do BD na atualidade
	Hoje temos diversos tipos de dados então se faz necessário de ter novas ferramentas que atendam essa demanda e assim tendo uma maior produtividade e exclência para resolver os problemas qeu acabam permeiando o ambiente de trabalho. 

- O que é SQL e NoSQL
	SQL armazena dados que tem relacionamento entre si, onde existe uma normalização das informações, ter uma consitência e evitar a duplicidade, ou seja, esquema de dados rígidos (Conhece o modelo e os dados que precisam ser inseridos). A complexidade de consultar podem ser bem complexas dependendo com o número de JOINS que podem ser utilizados para uma determinada query.
	NoSQL é mais flexível, são bancos mais robustos, foi criado para ser uma alternativa do SQL de forma complementar e não substituílo. Surgiu com necessidade de ter que armazenar um grande volume de dados e que não estejam estruturados, dependendo do contexto da organização o NoSQL faz mais sentido de usá-lo. Uma boa escabilidade vertical, recebe qualquer tipo de informação a complexidade da consulta acaba ficando mais simples

- Como se consulta um dado no NoSQL?
	Os documentos não tem um esquema definido mas é necessário ter um cuidados como no exemplo das consultas definindo as chaves a forma de consultar deve ser estudada antes e consequentemente tendo uma perfomance desejada. Uma API deve saber lidar com a falta de previsibilidade das informações, ou seja, o que ele deve armazenar e o que precisa não armazenar para saber quais informações serão necessárias para atingir o objetivo da organização

- Conhecer um SGBD de cada tipo é o suficiente pra iniciar?
	Impossível conhecer todos os tipos de SGBD porque sempre vai aparecendo ferramentas novas então, faria mais sentido conhecer o que cada um pode fazer e aplicar no seu contexto real qual dos modelos apresentados faz mais sentido para a sua realidade e com isso vai atender melhor o objetivo procurado.

- Evolução da arquitetura de sistemas e transições de estruturas
	Conforme o tempo passa as arquiteturas tem que evoluir junto com o sistema mas é necessário ter uma transição suave para que não pare os processos e continue o trabalho.

- DataLake e DataBricks
	5 capacidades básicas de dados é a ingestão, armazenamento, processamento, disponibilidade de informação, e segurança/governança.
	Uma grande gama de informações que são recebidas e é necessário separar o que é realmente necessário extrair de informação para que não fique apenas um monte de dados sem importância nenhuma no banco.

- Maiores desafios na hora de realizar um ETL
	Maior desafio é na parte de manipulação de dados

- Como gerada a demanda de daos e quem define o que serão coletados?
	Atuação próxima de quem desenvolve o projeto, ou seja, é importante ter um modelo descentralizado para assim de quem está filtrando esses dados acaba sabendo o que é mais coerente para o modelo.

- Engenheiro e Cientista de dados
	São perfis complementares, o papel do engnheiro está ligado a preparação da informação, precisa de mais cionhecimento técnico e deixar disponível para que o cientista possa utilizar para fazer a ánalise, criação de modelos e assim retirar alguns insights
