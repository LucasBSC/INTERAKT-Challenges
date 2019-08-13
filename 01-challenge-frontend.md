# Desafio: Aplicação de Gestão de Entregas

Bem-vindos ao desafio front-end da INTERAKT!

O objetivo principal do desafio é avaliar os seus conhecimentos sobre React, HTML, CSS e Javascript. Salientamos que não existe resposta certa ou errada para o desafio, muito menos pegadinhas!

Sem dúvidas, o mais importante é podermos entender o racional utilizado por cada decisão de implementação do código aliado à sua proficiência nas tecnologias abordadas, certo?

Vamos para os requisitos!

## Requisitos gerais

A aplicação a ser desenvolvida aborda um fluxo muito comum do setor logístico e trata-se de dois cadastros (CRUD's) simples: Entregas e Produtos.

Cada entrega deve ser composta de diversos produtos e ambas entidades possuem algumas propriedades listadas nos requisitos específicos.

Nós forneceremos uma API GraphQL para consulta e cadastro dos dados.

Recomendamos o uso da biblioteca AntDesign (https://ant.design/) para os componentes da UI

## Requisitos específicos

### Produto

- Descrição
- Preço
  - Deve possuir máscara para a moeda real ( ex.: R\$ 1.000.000,00 )

### Entrega

- Descrição
- Data
  - Deve ser restrito o componente de DatePicker de forma a impedir o cadastro de uma entrega retroativa
- Local
  - Deve ser selecionado a partir da API Google Places Autocomplete e salvo como objeto contendo endereço, latitude e longitude.
- Entregador
  - Deve ser selecionado um entregador dentre uma lista pré-carregada da API
- Produtos
  - Devem ser selecionados dentre a lista de produtos cadastrada previamente

Toda entrega cadastrada, recebe na API uma propriedade _estado_ (Pendente) como default.

### Lista de Entregas

- Descrição de _Entrega_
- Estado

Deve ser possível filtrar as entregas cadastradas por _range_ de _Data_, _Estado_, _Entregador_

A lista das entregas deve atualizar automaticamente quando houver alguma alteração no banco destes campos.

## Dicas e diferenciais

- Caso opte por construir sua própria API GraphQL, sinta-se à vontade! :D

- Valorizamos muito "confirmações" e "feedback" ao usuário das ações/respostas que são tomadas sob a interface.

- Escrever testes é muito bem visto.

- Commits e arquivos pequenos com responsabilidades limitadas e bem descritas serão muito bem avaliados.
