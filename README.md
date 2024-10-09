# Aplicação: Pesquisa Endereço

Essa aplicação faz a pesquisa de um endereço com base em um CEP, muito comum em formulários de cadastros em aplicações web.

## Modo de Funcionamento:
- É digitado o CEP do local desejado no campo específico dentro da pagina WEB.
- Com isso uma pesquisa é feita consultando uma API externa. 
- Essa requisição é feita através de uma instância de um objeto XMLHttpRequest. Ou seja, é feita uma requisição assíncrona dessas informações para uma API.
- E assim que a resposta é obtida é feita a população da aplicação FrontEnd.