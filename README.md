# Projetos JavaScript, HTML e CSS

Este repositório contém dois projetos diferentes desenvolvidos utilizando JavaScript, HTML e CSS.

## ⛽ Projeto 1: Calculadora Álcool ou Gasolina

Este é um projeto de uma calculadora que através da entrada de valores feita pelo usuário referentes ao preço da gasolina e álcool, a calculadora informa qual a melhor opção.

### Calculo:
```javascript
let calculo = (alcoolInput / gasolinaInput);

if(calculo < 0.7){
    /* Aqui compensa usar álcool */
    textResult.innerHTML = "Compensa usar Álcool";
} else {
    /* Aqui compensa usar gasolina */
    textResult.innerHTML = "Compensa usar Gasolina";
}

gasolinaSpan.innerHTML = "Gasolina R$ " + gasolinaInput;
alcoolSpan.innerHTML = "Álcool R$ " + alcoolInput;
```

## 👚 Projeto 2: E-Commerce Magazine Hashtag

Este é um projeto de uma loja de roupas simulada. Permite aos usuários navegar pelos produtos, adicionar itens ao carrinho e finalizar a compra.

### Funcionalidades principais:

- 📃 Listagem de produtos
- 🛒 Adição de produtos ao carrinho
- 💳 Finalização de compra

### Tailwind CSS
A estilização do projeto de E-Commerce foi feita utilizando o Tailwind CSS.

### Arquivos Tailwind CSS:
- `postcss.config.js`
- `tailwind.config.js`
