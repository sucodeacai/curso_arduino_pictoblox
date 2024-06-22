<center>

[🏠 Home](../README.md)

</center>

#

<h1 align="center">Pictoblox </h1>

## O que é?

<div align="center">

</div>

> Plataforma revolucionária de programação Python baseada em blocos para crianças e adolescentes aprenderem codificação por meio de projetos criativos e envolventes .
>
> Fonte: https://thestempedia.com/product/pictoblox/

## Conhecendo o Pictoblox

O primeiro passo é abrir o Pictoblox e iniciar nosso projeto craindo um arquivo do tipo Blocos, conforme a imagem a seguir:

![Projeto Reactjs](img/pictoblox/pictoblox_1.png)

Na imagem abaixo, o ícone que indica se há uma placa conectada ou não está destacado com um quadrado verde. No nosso caso, como ainda não conectamos a placa, o ícone de "sem conexão" é exibido. Para conectar, clique na opção "Conectar" no menu.

![Projeto Reactjs](img/pictoblox/pictoblox_2.png)

E em seguida selecionar a placa desejada, no nosso caso Arduino Uno.

![Projeto Reactjs](img/pictoblox/pictoblox_3.png)

Ao conectar a sua placa Arduino via USB no computador ela irá aparecer como uma opção, para realizar a conexão, clique em conectar.

![Projeto Reactjs](img/pictoblox/pictoblox_4.png)

Caso tenha ocorrido tudo bem o ícone de "conectado" é exibido, agora para iniciarmos nossa programação basta clicarmos em carregar, para poder liberar os blocos para serem utilizados no Arduino.

![Projeto Reactjs](img/pictoblox/pictoblox_5.png)

Na maioria das placas de Arduino, há um LED conectado ao pino 13, então como nosso primeiro código, vamos fazer ele piscar a cada 1 segundo com o código a seguir, para carregar o código na placa basta clicar em Carregar Código.

![Projeto Reactjs](img/pictoblox/pictoblox_6.png)

Caso tenha tudo ocorrido bem, o led **L** da nossa plca vai ficar piscando em intervalos de 1 segundo.

![Projeto Reactjs](img/pictoblox/pictoblox_7.gif)

Agora vamos atualizar nosso projeto, para exibir o estado do nosso led **L** no Monitor Serial. Para fazer isso vamos adicionar os blocos do tipo Comunicação, por meio do botão **Adicionar Extensão**, destacado na imagem.

![Projeto Reactjs](img/pictoblox/pictoblox_8.png)

Vamos pesquisar por **comunicação**, e adicionar o item destacado.

![Projeto Reactjs](img/pictoblox/pictoblox_9.png)

Atualizamos nosso código para definir a baud rate, que é a velocidade de comunicação serial entre a placa Arduino e outros dispositivos, como um computador. Além disso, adicionamos comandos para controlar o LED, permitindo que envie mensagens ao monitor serial. Agora, sempre que o LED é ligado, o Arduino envia 'Ligado' ao monitor serial; da mesma forma, quando o LED é desligado, envia 'Desligado'.

![Projeto Reactjs](img/pictoblox/pictoblox_10.png)

Após atualizar o código na sua placa Arduino, basca clicar em "Monitor Serial", para acompanhar as saídas de texto.

![Projeto Reactjs](img/pictoblox/pictoblox_11.png)

<center>

[🏠 Home](../README.md)

</center>
