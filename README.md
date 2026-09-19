# Projeto 30X - Página de vendas

Pacote completo da página de vendas do Projeto 30X.

## Estrutura

- `dist/index.html`: página completa, com HTML, CSS e JavaScript.
- `dist/assets/`: imagens reais utilizadas na página.
- `.openai/hosting.json`: configuração original de hospedagem do projeto.

## Publicação em hospedagem externa

O site é estático e não exige instalação, compilação ou banco de dados.
Publique o conteúdo da pasta `dist` na raiz pública da hospedagem.

Para visualizar localmente, abra `dist/index.html` no navegador.

## Campos que ainda devem ser substituídos

Busque no arquivo `dist/index.html` por:

- `{{CHECKOUT_URL}}`: link definitivo do checkout.
- `{{PREÇO}}`: preço da oferta.
- `{{VSL}}`: referência reservada para a VSL.

O checkout está centralizado na constante `CHECKOUT_URL`, no final do arquivo.
Ao trocar esse valor uma vez, todos os botões passam a usar o novo endereço.

