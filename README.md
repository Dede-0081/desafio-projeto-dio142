# desafio-projeto-dio142


Desafio de Projeto  de Transformação de Dados da dio.# Desafio de Projeto DIO: Processando e Transformando Dados no Power BI

Este projeto deu início a um desafio proposto no curso **Santander Bootcamp 2023 - Ciência de Dados com Python** da plataforma de cursos DIO, no qual preciso criar uma instância de banco de dados MySQL do Azure e integrar ao Power BI e tratar desses dados.

## 📝📝 Relatório Descritivo

1. Alteração de valores monetários de _Salary_ (Salário) na tabela **employee** para o tipo double preciso

2. Separação da coluna complexa _Address_ (Endereço) na tabela **employee**, separando por delimitador em *Number* (Número), *State* (Estado), *City* (Cidade) e *FU* (Federal Unit/Unidade Federativa)

3. Mescla das tabelas **employee** e **departament** associando o nome dos departamentos aos colaboradores

4. Mescla das tabelas **departament** e **dept_location** concatenando as colunas de nome do departamento e localização para que cada departamento-local seja único

5. Junção de colaboradores e respectivos nomes dos gerentes na tabela **employee** e mescla nas colunas de nome e sobrenome de cada colaborador e gerente.

## 📚📚 Dúvidas
**Por que apenas mesclar consultas e não combinar consultas nos casos supracitados?**

Mesclar consultas é para o momento em que desejamos apenas unir colunas entre tabelas, ou seja, trabalhando de forma colunar. Combinar consultas está em unificar apenas as linhas entre as tabelas. 


## 💻💻 Tecnologias Utilizadas

- Azure - plataforma de nuvem que possibilitou criar um banco de dados MySQL na nuvem
- Power BI - ferramenta de avaliação e visualização de dados da qual utilizamos para fazer a transformação de limpeza dos dados
- MySQL - sistema de gerenciamento de banco de dados usado, que utiliza a linguagem SQL como interface.
