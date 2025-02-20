# Desafio Advanced API

Este projeto é um desafio de automação de testes utilizando Cypress e outras ferramentas. Abaixo estão as instruções para configurar o ambiente e executar os testes.

## Ferramentas Necessárias

Para configurar o ambiente e executar os testes, você precisa instalar as seguintes ferramentas:

- **Node.js**: Gerenciador de pacotes e ambiente de execução para Javascript.
- **Cypress**: Ferramenta para automação de testes ponta a ponta.
- **VSCode**: Editor de código recomendado.
- **Cucumber**: Framework para testes baseado em BDD.

## Configuração do Ambiente

1. **Instale o Node.js**:
   - Baixe e instale o Node.js a partir do site oficial.

2. **Instale o Cypress**:
   - Execute o seguinte comando para instalar o Cypress:
     ```sh
     npm install cypress --save-dev
     ```

3. **Instale o Cucumber**:
   - Execute o seguinte comando para instalar o Cucumber:
     ```sh
     npm install --save-dev cypress-cucumber-preprocessor
     ```


## Executando os Testes
npx cypress run


## Desafio API
Documentação de todas APIs
https://www.advantageonlineshopping.com/api/docs/

Cenários de Teste
Procurar por um Produto (GET):

API: https://www.advantageonlineshopping.com/catalog/api/v1/products/search
Descrição: Criar um cenário que procure por um produto e traga apenas eles.
Atualizar a Imagem de um Produto (POST):

API: https://www.advantageonlineshopping.com/catalog/api/v1/product/image/{userId}/{source}/{color}
Descrição: Criar um cenário que atualize a imagem de um produto verificando se foi gerado um id para a nova imagem.

## Sinta-se à vontade para contribuir com este projeto. Para isso, siga os passos abaixo:

Faça um fork do projeto.
Crie uma branch para sua feature (git checkout -b feature/nova-feature).
Faça commit das suas alterações (git commit -m 'Adiciona nova feature').
Faça push para a branch (git push origin feature/nova-feature).
Abra um Pull Request.
