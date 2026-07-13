# Definição do MVP

## Problema
Issue ([#12266](https://github.com/inventree/InvenTree/issues/12266)) Mesmo com a opção "Initial stock data" habilitada no painel admin, o formulario de criação de peça não exibe campos para informar o estoque inicial.

## Solução do Problema (MVP)
Exibir o campo de estoque inicial no formulário de criação de Part quando a opção "Initial stock data" estiver habilitada, eliminando a necessidade do lançamento de estoque manual e separado.

## Justificativa de Valor
- Resolver um problema já indicado pela comunidade.
- Escopo pequeno e isolado.
- Impacto direto na experiencia do usuário no fluxo mais básico do sistema

## Justificativa de Viabilidade
- Área do codigo já mapeada
- Não exige mudança de schema de banco de dados
- Testavel de forma isolada

## Relação com o JTBD
Esse MVP atende a necessidade de visibilidade clara e confiança que um gerenciador de estoque precisa ter, reduzindo riscos para que aconteça erros na hora de registrar etoque inicial dado a ação de criar uma nova peça.



