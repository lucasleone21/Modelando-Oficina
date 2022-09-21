# Modelando-Oficina

Arquivo em formato PDF disponibilizado como Oficina

Modelagem de um banco de dados relacional para uma Oficina. Desafio proposto pela plataforma Dio.me

Neste modelo simplicado de uma Oficina temos algumas entidades como: Cliente, Mecanico, Equipe, OS(Ordem de serviço), Pedido, Serviços, Peças...

O Cliente faz um pedido de um serviço, relacionamento muitos para muitos, já que um cliente pode requisitar varios serviços e um serviço pode ter varios clientes

Um mecanico pode participar de varias equipes e uma equipe possui varios mecanicos, tambem temos um relacionamento muitos para muitos. 

Assim como em Equipes e Serviços, uma equipe pode ter varios serviços e um serviço pode ser realizado por varias equipes.

Tambem temos relacionamentos muitos para muitos entre Peças e OS e tambem entre OS e Serviços
