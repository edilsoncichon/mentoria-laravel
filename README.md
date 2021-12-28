# Projeto exemplo para ser usado na Mentoria Laravel.

Trata-se de um sistema web para controle financeiro pessoal.
Onde vamos usá-lo como exemplo para aplicar os conceitos principais do Laravel.

CONTROLE DE DESPESAS

1. `contas` (tabela)
	- tipo 				 - varchar(255) - 'PAGAR' / 'RECEBER'
	- cliente_fornecedor - varchar(255) 
	- valor				 - decimal(10,2)
	- parcela			 - int
	- forma_pagamento	 - varchar(255)
	- dt_vencimento	 	 - date
	- dt_pagamento		 - date

2. `cliente_fornecedor` - tabela

3. USUÁRIOS
	- USAR O SISTEMA DE AUTENTICAÇÃO PADRÃO DO LARAVEL.
	- Usuários possuem contas a pagar/receber.
