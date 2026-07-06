 # Descrição do Sistema
 
O Inventree é um sistema de gerenciamento de inventario de código aberto, planejado para auxiliar na gestão de estoques. Buscando ser uma alternativa leve e de fácil uso, visando aplicações de pequenas e médias empresas ou para hobby. Utiliza de uma forte logica de negócios para manter o histórico de rastreamento do estoque, para que o usuário tem acesso rápido as informações. 

O sistema é desenvolvido em python e django, armazenando dados em um banco de dados relacional e os disponibiliza através de uma aplicação WEB. Tendo como opção também a integração com outra aplicação através de uma API.        

O sistema possui algumas funcionalidades principais, são elas:

- Parts: É o componente principal do sistema, representam os itens que serão estocados e organizados pelo sistema;
- Suppliers: É uma funcionalidade que tem como função gerenciar fornecedores, podendo realizar operações sobre os fornecedores do usuário;
- Instant Stock Knowledge: Visualizar informações sobre o estoque e as parts, de forma rápida e direta, permitindo filtrar dados e organizar informações;
- Bill of Materials: Gerencia a lista de materiais que uma part precisa para ser criada, assim permitindo criar pedidos para essas;
- Build Parts: É a funcionalidade responsável por rastrear o progresso de construção de novas parts e estoques da mesma;
- Report: É capaz de gerar relatórios baseados nas movimentações realizadas no estoque;

## Qual o problema o sistema resolve  ?

O InvenTree busca atender a demanda sobre um sistema de gerenciamento de estoques de acesso livre que possa ser integrado a outros sistemas de maneira fácil, facilitando assim que pequenas e médias empresas possam gerenciar seus estoques.

## Qual "trabalho" o usuário deseja realizar ?

O usuário que busca o InvenTree, tem como necessidade um sistema para auxiliar no gerenciamento de um possível estoque, facilitando assim a administração do mesmo. Podendo adicionar, editar e remover itens, gerenciar fornecedores e agendar pedidos, acompanhar processos de montagem de itens e gerar relatórios sobre o estoque.

## Onde há falhas ou oportunidades ? 

O Projeto possui uma label no github, chamada roadmap, onde são categorizados issues que estão no caminho de serem implementadas e priorizadas. Entre alguma dessas 