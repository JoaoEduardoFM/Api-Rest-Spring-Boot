# Api-Controle-de-gastos

![header](https://user-images.githubusercontent.com/90796699/229205799-b4f7abac-885c-4cb2-9c24-67aae1f2b452.png)

> Status: Em desenvolvimento ⚠️

### É uma aplicação planejada por mim, onde realizo o CRUD e operações de controle de gastos.

## Alguns campos no modelo principal são:

## categoria
+ codigo 
+ nome

## Endereco
+ logradouro;
+ numero;
+ complemento;
+ bairro;
+ cep;
+ cidade;
+ estado;

##lancamento
+ codigo
+ descricao
+ data vencimento
+ data pagamento
+ valor
+ observacao
+ tipo
+ categoria
+ pessoa

##pessoa
+ codigo
+ nome
+ endereco
+ ativo

##Tipo Lancamento
+ RECEITA
+ DESPESA

## Technologies Used:
![header](https://user-images.githubusercontent.com/90796699/228732700-385f1245-70e2-4afa-8fcb-3838c43cc3d1.png)
![header](https://user-images.githubusercontent.com/90796699/228732963-6bafac5b-bb12-4e8d-b72a-47b3798f7bc3.png)
![header](https://user-images.githubusercontent.com/90796699/229381110-73a2592a-5e58-4948-ae38-a179cc119e10.png)
<table>
  <tr>
    <td>Java</td>
    <td>spring-boot</td>
    <td>H2</td>
  </tr>
  <tr>
    <td>11</td>
    <td>2.5.3</td>
    <td>h2</td>
  </tr>
</table>

## Desenvolvimento concluído.

1) Aplicação rest de cadastro de registros(Categoria, Endereço, Lançamento, pessoa).
2) Gastos referenciado de um cliente.
3) Ativando ou desativando conta.
4) tratado todos os tipo de retorno rest (Ex: 201 created).
5) Adicionado Swagger.

## Esses recursos estão em desenvolvimento:

- Em desenvolvimento ⚠️
1) Adicionar autenticação JWT.

