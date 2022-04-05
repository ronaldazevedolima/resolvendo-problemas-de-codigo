# Como resolver problemas de código? 

## PROBLEMA

Você é uma pessoa desenvolvedora que foi contratada para resolver o problema de uma loja de produtos de tecnologia. 
Nessa loja, a pessoa proprietária deseja ser capaz de pesquisar um equipamento através do id cadastrado.

### Parte I
 
No arquivo ```exercise.js```, você tem um exemplo de como esses produtos estão armazenados nos computadores da loja.
Como pode observar, as informações de cada produto estão dentro de um objeto, sendo que tdos os objetos que representam os produtos estão dentro de um array. 
  
Sua tarefa é criar um algoritmo que, ao receber o id numérico de um produto, retorne uma string com o nome do produto correspondente. 

### Parte II

A pessoa proprietária da loja gostou muito do seu trabalho e te chamou para resolver um novo desafio. 
 
Agora, além de trazer o nome do produto, ela quer que você traga também o preço em string no formato:
 
```nomeDoProduto - R$000,00```
 
Altere o codigo anterior para atender aos requisitos propostos.

### Parte III

Novas pessoas colaboradoras entraram na equipe da loja e, por não conhecerem todos os ids de produtos, têm feito buscas por produtos indexistentes. 

A pessoa proprietária lhe chamou para resolver esse problema. 
 
Altere o código anterior para que se receber um número menor ou igual a 0 ou um número maior que o valor do último produto listado no array seja exibida uma mensagem de erro no formato: 

```Infelizmente o id numeroDoIdDigitado não existe.``` 


### Parte IV

Chegaram novos produtos à loja que aidna não estão listados no array de techProducts. 
 
A pessoa proprietária da loja te contratou para criar um programa no qual seja possível registrar dinamicamente os novos produtos. 

Crie um algoritmo que receba o nome, o id e o preço de um produto e adicione os valores recebidos como valores de um objeto para criar o novo produto. Adicione o produto cadastrado no array techProducts.  

### Parte V - Manipulando o DOM

A loja de produtos de tecnologia está crescendo e a pessoa proprietária contratou uma desenvolvedora front-end para criar uma interface na qual seja possível, através de um input, receber o id de um produto e obter o nome dele através de um alert. 

Na pasta ```project2``` você encontra os arquivos ```index.html``` e ```style.css``` usados para criar a interface.

Seu desafio é, a partir do código desenvolvido na **Parte I**, manipular o DOM para executar a busca do nome do produto no array ```techProducts``` através do ```id``` digitado pela pessoa usuária no campo de input. 

```DICA:``` você vai precisar utilizar eventos para conseguir associar a captura do valor do id ao click do botão. 