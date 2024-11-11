# Exemplo de Requisição com HTMX

Este projeto demonstra como usar a biblioteca HTMX para realizar uma requisição GET e carregar dados de uma API diretamente na página, sem necessidade de JavaScript adicional. HTMX é uma biblioteca leve que permite adicionar interatividade ao HTML de maneira declarativa.

## Funcionalidades

- Realiza uma requisição GET para a API JSONPlaceholder, uma API de teste comum para desenvolvimento.
- Insere os dados dos usuários retornados pela API no elemento de destino, de forma dinâmica.
- Exibe os dados no formato de uma lista com bordas estilizadas para visualização clara.

## Como Funciona

Este exemplo utiliza HTMX para carregar dados ao clicar em um botão. Quando o botão "Carregar Usuários" é pressionado:

1. A biblioteca HTMX envia uma requisição GET para a URL fornecida (`https://jsonplaceholder.typicode.com/users`).
2. O atributo `hx-target="#user-container"` define onde os dados carregados serão inseridos — neste caso, dentro do `div` com `id="user-container"`.
3. O atributo `hx-swap="innerHTML"` especifica que o conteúdo atual do `div` será substituído pelo novo conteúdo recebido.

## Requisitos
Para visualizar o exemplo localmente, basta abrir o arquivo HTML em um navegador com conexão à internet, pois tanto o HTMX quanto a API são carregados de fontes externas.

## Recursos Adicionais
HTMX Documentation
[HTMX Documentation](https://linkedin.com/in/iagommendes](https://htmx.org/docs/)
