
# Integrasky: SAP B1 x SalesForce
[Especificação Técnica Integração SAP B1/Liberali x Sales Force](https://f1edb3594a-my.sharepoint.com/:w:/g/personal/diogo_nascimento_k33p_com_br/EbpEe3JCTd9EsaXZGwwuxn4BB7Ln0p6XWtZeZaW20XgHYQ?rtime=R6sRLEuU20g)

|Objeto                    |Identificador|Origem     |Destino    |Sprint|Requisição B1|jsonata depara|Requisição SF|
|--------------------------|-------------|-----------|-----------|------|-----------------------|--------------|-----------------------|
|Clientes                  |OCRD         |B1         |Sales Force|1     |                       |              |                       |
|Condição de Pagamento     |OCTG         |B1         |Sales Force|1     |                       |              |                       |
|Contatos                  |OCPR         |B1         |Sales Force|1     |                       |              |                       |
|Filiais                   |OBPL         |B1         |Sales Force|1     |                       |              |                       |
|Produtos                  |OITM         |B1         |Sales Force|1     |OK                       |              |                       |
|Vendedores                |OSLP         |B1         |Sales Force|1     |                       |              |                       |
|Duplicatas                |INV          |B1         |Sales Force|2     |                       |              |                       |
|Lista de Preço¹           |OPLN         |B1         |Sales Force|2     |                       |              |                       |
|Notas Fiscais             |OINV         |B1         |Sales Force|2     |                       |              |                       |
|Saldo Estoque Geral¹      |OITW_FULL    |B1         |Sales Force|2     |                       |              |                       |
|Saldo Estoque por filiais¹|OITW_BPL     |B1         |Sales Force|2     |                       |              |                       |
|Agrônomos                 |@K_AGRONOMOS |B1         |Sales Force|3     |                       |              |                       |
|Caderno de Campo¹         |@AGRV_UNPF5  |Sales Force|B1         |3     |                       |              |                       |
|Cultura do Local¹ ²       |@???_CULT    |Sales Force|B1         |3     |                       |              |                       |
|Propriedades              |@AGRV_UNPF   |B1         |Sales Force|3     |                       |              |                       |
|Talhões                   |@AGRV_UNPT   |B1         |Sales Force|3     |                       |              |                       |

> ¹ Cadastros que possuem regras de negócio complexa, ou não possuem acesso direto pela service layer através de um UDT ou UDO, recomendado criar Calculation View para expor dados.
  
> ² Definir Prefixo tabela organização; Criar Setup criação tabela Usuário/Objeto



### Tools

 - [JSONata](https://docs.jsonata.org/overview.html)
 - [Integra Sky](https://app.integrasky.cloud)
