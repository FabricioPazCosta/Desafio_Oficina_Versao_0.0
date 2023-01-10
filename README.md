# Desafio_Oficina_Versao_0.0
 Modelo Conceitual Oficina

Clientes levam veículos a oficina mecânica para serem consertados ou para passarem por revisões periódicas
O cliente autoriza a execução dos serviços.

Veículo
Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenchem uma OS com data de entrega.
Tem nome, registro e placa

Revisão
Os clientes levam os veículos para a revisões.
Os mecânicos preenchem as ordens de serviços com data de entrega

A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão de obra.
O valor de cada peça também irá compor a OS.

Ordem se Serviço
Cada OS possui: n°, data d emissão, um valor, status e uma data para conclusão dos trabalhos.
Processo de Criação Banco de Dados
Uma OS pode ser composta por vários serviços e um mesmo serviço pode estar contido em mais de uma OS.
Uma OS pode ter vários tipos de peças e uma peça pode estar presente em mais de uma OS.
Os mecânicos conserta ou revisa os veículos.


Equipe Mecânico
A mesma equipe avalia e executa os serviços.
Os mecânicos possuem código, nome, endereço e especialidade

Consertar
Os clientes levam os veículos para serem consertados.

Tabela Referência Mão de Obra
Valores referente aos serviços executados pelos mecânicos.

Peça
Uma peça tem um nome, código e descrição.
