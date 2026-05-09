# SQL-FULL
SQL DATA BASE CONTENT

Este repositório é fruto de meus estudo com o NotebookLM.


# Contexto e Objetivos
Aqui registro meus estudos e práticas em SQL Server, priorizando a performance e a entrega de dados otimizada. 
Acredito que a qualidade da gestão de dados é o diferencial de qualquer aplicação moderna.

Este repositório foi estruturado com o auxílio do NotebookLM, que utilizei para processar e sintetizar a documentação técnica, transformando-a nas implementações 
práticas e otimizações de consultas aqui apresentadas para ambientes Microsoft.

# Curadoria de Fontes
- https://www.youtube.com/watch?v=aYt6pKsBws8
- https://www.seduc.ce.gov.br/wp-content/uploads/sites/37/2012/08/redes_de_computadores_manual_do_professor_banco_de_dados.pdf
- https://datacoaching.io/wp-content/uploads/2024/06/Advanced-SQL-for-Beginners-Free-Download.pdf
- https://faculty.cc.gatech.edu/~jarulraj/courses/4420-f21/slides/03-advanced-sql.pdf
- https://theswissbay.ch/pdf/Gentoomen%20Library/Databases/mssql/Advanced%20SQL%20Database%20Programmers%20Handbook%202003.pdf

# Engenharia de Prompts 
Ferramenta de Apoio: NotebookLM.
Processo: O conteúdo foi refinado através de múltiplas iterações de prompts, buscando as melhores formas de extrair e organizar o conhecimento técnico aqui apresentado.
Foco: Qualidade, agilidade e otimização de consultas em ecossistemas Microsoft.

# Miniguia de Estudo 

## **Um glossário com os principais conceitos aprendidos**

* SELECT: Comando principal para a extração e visualização de dados de uma ou mais tabelas.
* FROM: Define a origem dos dados, indicando em qual tabela a consulta deve buscar as informações.
* WHERE: Filtro fundamental utilizado para extrair apenas os registros que atendem a uma condição específica.
* JOIN (Inner, Left, Right): Operação que permite combinar dados de duas ou mais tabelas baseando-se em uma coluna comum entre elas.
* PRIMARY KEY (Chave Primária): Campo ou conjunto de campos que identifica de forma exclusiva cada registro em uma tabela.
* FOREIGN KEY (Chave Estrangeira): Campo que estabelece um link entre os dados de duas tabelas, garantindo a integridade referencial.
* GROUP BY: Agrupa linhas que têm os mesmos valores em colunas específicas, geralmente usado com funções de agregação.
* ORDER BY: Define a ordem de exibição do resultado da consulta (ascendente com ASC ou descendente com DESC).
* DISTINCT: Cláusula utilizada para retornar apenas valores diferentes (exclusivos), eliminando duplicatas no resultado.
* INSERT INTO: Comando utilizado para inserir novos registros (linhas) em uma tabela existente.
* UPDATE: Comando para modificar dados já existentes em uma tabela, geralmente acompanhado de um WHERE para evitar alterações indesejadas.
* DELETE: Comando para remover registros de uma tabela.
* VIEW: Uma tabela virtual baseada no conjunto de resultados de uma consulta SQL, facilitando o acesso a lógicas complexas.
* STORED PROCEDURE: Um conjunto de comandos SQL que pode ser armazenado e executado no servidor para automatizar tarefas.
* TRANSACTION (COMMIT/ROLLBACK): Garante que um conjunto de operações seja executado por completo ou totalmente revertido em caso de erro.
* HAVING: Filtro aplicado especificamente aos resultados de um agrupamento (GROUP BY), onde o WHERE não pode atuar.
* CONSTRAINT: Regras aplicadas às colunas de uma tabela (como NOT NULL ou UNIQUE) para manter a qualidade dos dados.

## **Um conjunto de prompts reutilizáveis que possam apoiar futuras revisões sobre o tema**

Prompt: "Atue como um DBA especializado em [SQLSERVER]. Crie o script DDL para uma tabela chamada [TABELA]
que armazene os dados. Inclua chaves primárias, índices para as colunas de busca frequente e comentários em cada coluna."

Prompt: "Converta este modelo de dados em JSON para um script de criação de tabela SQL compatível com [Banco de Dados]: [Colar o JSON aqui]."

Prompt: "Escreva uma query SQL que retorne [DADO] unindo as tabelas [Tabela A] e [Tabela B]. Considere um relacionamento de [1:N] e
aplique um filtro para [condição]. Use aliases claros e siga as melhores práticas de legibilidade."

Prompt: "Crie uma consulta utilizando Window Functions (ROW_NUMBER ou RANK) para identificar [ex: os últimos registros de cada usuário] na tabela [Nome]."

Prompt: "Analise a query abaixo e sugira melhorias de performance, considerando o uso de índices,
redução de subqueries e substituição de cursores por operações baseadas em conjuntos"

Prompt: "Escreva uma Stored Procedure para o SQL Server que realize o CRUD da tabela [Nome]. Garanta que existam tratamentos de erro com TRY CATCH e controle de transação."

Prompt: "Documente o que cada parte deste script SQL faz, detalhando a lógica dos joins e a finalidade das tabelas temporárias"

