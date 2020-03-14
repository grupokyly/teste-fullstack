![grupo-kyly](./images/logo.png)

# Teste Full Stack - Grupo Kyly

O teste consiste em criar uma API REST que busca produtos pelo código, descrição a partir de uma palavra chave. 
Faça o download do arquivo [sample_db.csv](./sample_db/sample_db.csv) que contém o banco de dados que deve ser usado na busca. 
Ele contém os Ids, códigos de produto, descrição do produto, cor do produto, descrição da cor, código do tamanho, descrição do tamanho.


###### Exemplo
| Id            | Produto| DescProduto   | Cor | DescCor         | Tamanho | DescTamanho|
|---------------|--------|---------------|-----|-----------------|---------|------------|
| 105735.6532.1 | 105735 | CONJUNTO MASC.|6532 |AZUL 19-4049 KYLY|1        |P           |
| 105801.4372.2 | 105801 | VESTIDO FEM.  |4372 |VERMELHO         |2        |6           |
| 105725.4372.4 | 105725 | CAMISETA MASC.|4372 |VERMELHO         |4        |GG          |




Também são fornecidas duas listas de produtos que devem ser utilizadas para priorizar os resultados da busca. 
 - A lista 1 tem mais prioridade que a lista 2. Ou seja, se dois produtos casam com os criterios de busca, aquele que está na lista 1 deverá ser exibido primeiro em relação àquele que está na lista 2. Os que não estão em nenhuma das listas são exibidos em seguida.

As listas podem ser encontradas na raiz deste repositório ([lista_relevancia_1.txt](lista_relevancia_1.txt) e [lista_relevancia_2.txt](lista_relevancia_2.txt)).
Os resultados devem ser retornados paginados de 15 em 15 registros.

Escolha as tecnologias que você vai usar e tente montar uma solução completa para rodar a aplicação.

-----

### Requisitos

- Criar um frontend para realizar a busca com uma UX elaborada
- Criar uma solução de autenticação entre o frontend e o backend
- Criar uma ramificação deste repositório 
- Criar um diretório src com a sua implementação
- Criar um Pull request para mesclar sua solução à este repositório
- Criar seu CV atualizado utilizando a formatação do git na ramificação
