cliente (id_cliente, nome, cpf, email, localização)
 |
 |
 |
produto (id_produto, nome_produto, preco, FK(id_cliente))
 |
 |
 |
/|\
venda (id_venda, qtde_produto, total_preco, local_entrega, FK(id_cliente), FK(id_produto))
