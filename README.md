# desafio02-ignite-reactjs

## Desafio 01 - Criando um hook de carrinho de compras

### Sobre o desafio: 
Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS
Essa será uma aplicação onde o seu principal objetivo é criar um hook de carrinho de compras. Você terá acesso a duas páginas, um componente e um hook para implementar as funcionalidades pedidas nesse desafio:

- Adicionar um novo produto ao carrinho;
- Remover um produto do carrinho;
- Alterar a quantidade de um produto no carrinho;
- Cálculo dos preços sub-total e total do carrinho;
- Validação de estoque;
- Exibição de mensagens de erro;
- Entre outros.

Para esse desafio, além dos conceitos vistos em aula utilizou-se algumas coisa novas para deixar a nossa aplicação ainda melhor.

### Fake API com JSON Server
Assim como foi utilizado o MirageJS no módulo 2 para simular uma API com os dados das transações da aplicação dt.money, foi utilizado o JSON Server para simular uma API que possui as informações dos produtos e do estoque.

### Preservando carrinho com localStorage API
Para preservar os dados do carrinho mesmo se fecharmos a aplicação, utilizou-se o localStorage API.
Essa é uma API que permite persistir dados no navegador em um esquema de chave-valor (semelhante ao que temos com objetos JSON).

### Mostrando erros com toastify
Para mostrar os erros em tela, foi utilizada a lib react-toastify. Ela ajuda a mostra informações temporárias e rápidas de uma forma bem bonita.


![image](https://user-images.githubusercontent.com/74268252/126845414-48c18f6c-f39b-409a-aff1-bd0b9bd4401f.png)

![image](https://user-images.githubusercontent.com/74268252/126845440-fe041186-1e4b-43b6-b436-318cb71d35d1.png)

![image](https://user-images.githubusercontent.com/74268252/126845461-fee330a3-b380-4c0b-84c2-f0681fb2104d.png)


