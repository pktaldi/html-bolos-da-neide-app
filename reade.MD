cliente (id_cliente, nome, cpf, email)
 |
 |
 |
produto (id_produto, nome_produto, preco, FK(id_cliente))
 |
 |
 |
/|\
venda (id_venda, qtde_produto, total_preco, FK(id_cliente), FK(id_produto))
