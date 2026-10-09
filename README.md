Buscador de CEP e Mini Pokédex

Este projeto reúne três exercícios de JavaScript em uma única aplicação: validação de pedidos, consulta de CEP e busca de Pokémon. A proposta é colocar em prática conceitos importantes da linguagem por meio de situações que envolvem dados, requisições e interação com a página.

Na primeira parte, uma lista de pedidos é analisada para identificar dados válidos, separar os pedidos pagos e calcular o valor total faturado. Os resultados são organizados e exibidos no console.

O buscador de CEP utiliza a API ViaCEP para consultar informações de endereço, como rua, bairro, cidade e estado. Também mantém um histórico das consultas realizadas durante o uso da página e apresenta mensagens para situações como CEP inválido, endereço não encontrado e falhas de conexão.

A Mini Pokédex utiliza a PokéAPI para buscar Pokémon pelo nome e apresentar sua imagem e seus tipos. As duas ferramentas utilizam async/await, fetch e tratamento de erros para lidar com as requisições de forma assíncrona.

O projeto também aplica validação de entradas, manipulação do DOM, criação dinâmica de elementos HTML e estados de carregamento e erro, tornando a experiência mais clara para quem utiliza a página.

Tecnologias utilizadas: HTML5 e JavaScript.

Arquivos do projeto: index.html, responsável pela estrutura da página, e app.js, que contém a lógica de validação, as consultas às APIs e a manipulação dos resultados.

Para executar, abra o arquivo index.html em um navegador com acesso à internet. O arquivo app.js deve estar na mesma pasta. As consultas de CEP e Pokémon dependem do funcionamento das APIs externas.

O projeto permite praticar desde operações com arrays até o consumo de APIs, servindo como exercício de integração entre JavaScript, HTML e dados externos.
