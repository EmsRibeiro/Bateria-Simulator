## Explicação
O projeto simula uma bateria no navegador. O usuário pode interagir usando o mouse ou o teclado. Cada botão representa uma parte da bateria e, ao ser pressionado, emite um som correspondente e exibe uma animação visual temporária.

## Funcionalidades

### Interação via Mouse
O JavaScript seleciona todos os elementos com a classe `.drum` e percorre cada um deles com um loop `for`. Para cada botão, é adicionada uma função de callback que aciona o som e a animação ao ser clicado.

### Interação via Teclado
Foi adicionado um `addEventListener` para o evento `keydown`. Quando uma tecla correspondente é pressionada, a função `makeSound` é chamada, reproduzindo o som apropriado. A tecla pressionada também aciona a animação visual do botão correspondente.

## Observações
- A função `toLowerCase()` é usada para garantir compatibilidade entre letras maiúsculas e minúsculas ao pressionar teclas.
- Este projeto foi desenvolvido como exercício de fixação de conceitos aprendidos no curso Full Stack Turbo da TipsCode.
