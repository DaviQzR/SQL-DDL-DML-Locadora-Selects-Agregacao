# SQL-DDL-DML-Locadora-Selects-Agregacao

Considere o diagrama abaixo:

![image](https://github.com/DaviQzR/SQL-DDL-DML-Project-Select-Join/assets/125469425/2cdd12f5-82a9-4a70-bd61-a431b77ebab9)

Criar as tabelas da forma que foram diagramadas, obedecendo as seguintes restrições:

--> A coluna users_id da tabela associativa é FK da coluna id, tabela users

--> A coluna projects_id da tabela associativa é FK da coluna id, tabela projects

--> A coluna date da tabela projects deve verificar se a data é posterior que 01/09/2014.
Caso contrário, o registro não deve ser inserido

--> A PK de projects deve ser de auto incremento, iniciando em 10001, com incremento de
1

--> A PK de users deve ser de auto incremento, iniciando em 1, com incremento de 1

--> O valor padrão da coluna password da tabela users, deverá ser 123mudar

--> A coluna username da tabela users deve ter restrição de unicidade.

--> Modificar a coluna username da tabela Users para varchar(10)

--> Modificar a coluna password da tabela Users para varchar(8)

Inserir os dados abaixo:

![image](https://github.com/DaviQzR/SQL-DDL-DML-Project-Select-Join/assets/125469425/b62e2044-964c-4b27-ae53-140bcfd0e5fd)

Considerar as situações:

- O projeto de Manutenção atrasou, mudar a data para 12/09/2014
- O username de aparecido (usar o nome como condição de mudança) está feio, mudar para
Rh_cido
- Mudar o password do username Rh_maria (usar o username como condição de mudança)
para 888@*, mas a condição deve verificar se o password dela ainda é 123mudar
- O user de id 2 não participa mais do projeto 10002, removê-lo da associativa

Fazer:


a) Adicionar User
(6; Joao; Ti_joao; 123mudar; joao@empresa.com)

b) Adicionar Project
(10004; Atualização de Sistemas; Modificação de Sistemas Operacionais nos PC's; 12/09/2014)

Consultar: 

• Não esquecer de rever as restrições de datas

1) Consultar, num_cadastro do cliente, nome do cliente, titulo do filme, data_fabricação
do dvd, valor da locação, dos dvds que tem a maior data de fabricação dentre todos os
cadastrados.
2) Consultar Consultar, num_cadastro do cliente, nome do cliente, data de locação
(Formato DD/MM/AAAA) e a quantidade de DVD ́s alugados por cliente (Chamar essa
coluna de qtd), por data de locação
3) Consultar Consultar, num_cadastro do cliente, nome do cliente, data de locação
(Formato DD/MM/AAAA) e a valor total de todos os dvd ́s alugados (Chamar essa
coluna de valor_total), por data de locação
4) Consultar Consultar, num_cadastro do cliente, nome do cliente, Endereço
concatenado de logradouro e numero como Endereco, data de locação (Formato
DD/MM/AAAA) dos clientes que alugaram mais de 2 filmes simultaneamente
