
# Projeto do curso "ETL com Integration Services" da Alura
Criação de um DW utilizando conceitos de Modelagem Dimensional (Star Schema e Snow Flake), e integração de dados via Integration Services 2019.

>O SQL Server Integration Services é uma plataforma para criar integração de dados em nível empresarial e soluções de transformações de dados. Use Integration Services para solucionar problemas empresariais complexos copiando ou baixando arquivos, carregando data warehouses, limpando e minerando dados e gerenciando objetos SQL Server e dados.  
>*Fonte: https://docs.microsoft.com/pt-br/sql/integration-services/sql-server-integration-services?view=sql-server-ver16*

## Ferramentas utilizadas

- Para armazenamento utilizamos o **SQL Server 2019** e  o para consultas no banco **Microsoft SQL Server Management Studio 18**;
- Para criação de tabelas, modelagem e ETL, utilizamos o **Visual Studio 2019** com **Data Tools** + extensão do **SQL Server Integration Services Projects**.

## Conceitos e técnicas utilizadas

- **Levantamento de requisitos utilizando Matriz Dimensão Indicador;**
![Não foi fornecido texto alternativo para esta imagem](https://media-exp1.licdn.com/dms/image/C4E12AQG8TLqI5e7elg/article-inline_image-shrink_1000_1488/0/1590246203291?e=1665014400&v=beta&t=A4n2rQEOuQ4WSkZ9xcy7STYbzzEeeJgUPpAIw9dk4Ko)
*https://www.kimballgroup.com/1999/12/the-matrix/*

- **Modelagem dimensional**
  - Star Schema e Snow Flake;
  - Tabelas Fatos e Dimensões (Incluindo Tabela Tempo/Calendário).
  
 ![DW](https://user-images.githubusercontent.com/25754870/183221637-a52d559e-0710-42a6-a480-4761447f7cf3.PNG)
 *Diagrama do banco de dados utilizado para o Datawarehouse*

- **ETL (Extract, Trannsform, Load)**
  - Extração de dados de Planilhas, Flat files (csv,txt) e SQL Server;
  - Traformação de dados, conversão de tipo de dados, remoção de linhas duplicadas, funções de tratamento de texto, junção de datasets; 
  - Carga em banco de dados SQL Server,  SDC tipo1 (Slowly changing dimension);
  
![ex_tratamento](https://user-images.githubusercontent.com/25754870/183251896-fba1eb90-3223-4f68-969d-1faddb174057.PNG)
*Exemplo de tratamento de dados*

- **Visual Studio**
  - Criação de projeto e pacotes;
  - Utilização de parametrôs de pacote;
  - Criação e execução de pacotes.
  
![projeto_visual_studio](https://user-images.githubusercontent.com/25754870/183251202-91a5bfa7-8a49-4f42-8c93-af00e6026fdb.PNG)  
*Projeto criado no Visual Studio*

## Certificados
- [Business Intelligence: trabalhando com Data Warehouse](https://cursos.alura.com.br/user/ericknishimoto/course/business-intelligence-introducao-inteligencia-empresarial/formalCertificate)
- [ETL com Integration Services: modelo de dados](https://cursos.alura.com.br/user/ericknishimoto/course/business-intelligence-sql-server-e-integration-services/formalCertificate)
- [ETL com Integration Services: transformação de dados](https://cursos.alura.com.br/user/ericknishimoto/course/business-intelligence-sql-server-e-integration-services-parte2/formalCertificate)
