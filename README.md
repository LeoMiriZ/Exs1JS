# Exs1JS-HTML

## Exercício 1

Crie uma página HTML, com JavaScript, para resolver o problema dado:

Marquinhos adora colecionar cards. A última edição de sua coleção favorita, existiam seis cards diferentes, numerados de 1 a 6.

Porém, ao comprar o pacote com os cards, Marquinhos percebeu que o pacote continha apenas cinco cards (um estava faltando).

Sua tarefa é ajudar Marquinhos, escrevendo um programa onde, depois dele ter fornecido os números dos cinco cards que estavam no pacote, mostre em um div qual é o número do card faltante.

Por exemplo, se Marquinhos fornecesse os valores 3, 2, 5, 6 e 4, o programa deveria exibir o número 1 (pois é o valor que falta para completar a sequência). Em outro exemplo, se Marquinhos fornecesse os valores 1, 2, 4, 5 e 3, o programa deveria exibir o número 6.

Repare que Marquinhos pode fornecer os números em qualquer ordem!

Se por acaso Marquinhos digitar algum valor menor do que 1, ou maior do que 6, o programa deve exibir uma mensagem de erro no div.

Não se esqueça de validar o conteúdo de todos os campos antes de resolver o problema. Caso algum campo esteja inválido, exiba uma mensagem de erro no div.

## Exercício 2

Crie uma página, como mostrada na figura abaixo, utilizando HTML e JavaScript, para simular a tela de entrada de senha de um sistema.

No sistema, o usuário pode digitar sua senha tanto pelo teclado convencional, como pelo teclado numérico mostrado na tela. Os botões com os números de 0 a 9 devem apenas acrescentar o respectivo dígito ao final do campo de senha.

O botão Validar deverá verificar se a senha fornecida é "1234". Se sim, deve exibir uma mensagem de sucesso em um div. Se não for, deve exibir uma mensagem de erro no div.

## Exercício 3

Crie uma página, utilizando HTML e JavaScript, para criar uma tabela povoada com base em um array.

O array deve ser preenchido com 10 objetos fixos, criados por você 😅, da forma abaixo:

let pessoas = [
    {
        id: 1,
        nome: "André",
        email: "andre@espm.br",
        idade: 36,
        cargo: "Professor"
    },
    ...
];
 

A tabela deve ser preenchida quando o usuário clicar sobre o botão "Preencher Tabela".

