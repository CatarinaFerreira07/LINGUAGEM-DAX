# LINGUAGEM-DAX
TIPOS DE CÁLCULOS NO DAX
NOVA MEDIDA:Cria medidas para serem inseridas em gráficos
São calculadas somente no visual

MEDIDA RÁPIDA = Utiliza IA

NOVA COLUNA: Cria colunas na tabela utilizando dax
São calculadas e mantidas na tabela/modelo
Não aparecem no Power Query

NOVA TABELA: Cria tabelas udsando DAX
São calculadas e mantidas no modelo
Não aparecem no Power Query

EXEMPLOS:
SOMA Qtd = SUM(Pedidos[quantidade])
Valor total = Pedidos[quantidade] * Pedidos[preço unitário)
Média Vendas= Average(Pedidos[Valor Total])
Soma Meta= SUM(Metas[Valor])
qtdPedidos= DISTINCTCOUNT(Pedidos[código do Pedido])

