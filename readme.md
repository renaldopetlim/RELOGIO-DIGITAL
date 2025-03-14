# Relógio Digital
Este é um projeto simples de relógio digital que exibe a hora atual de forma dinâmica.

## Tecnologias Usadas:
- HTML - O código HTML é composto pela estrutura básica para exibir o relógio na página.
- CSS - O CSS aplica uma aparência simples e moderna ao relógio digital.
- JavaScript - O JavaScript é responsável por atualizar a hora a cada segundo.

### Descrição do HTML:
- A `div` com o `id="clock"` serve como o container para o relógio.
- A `div` com o `id="time"` exibe o tempo atual, e sua classe é usada para aplicar o estilo.
- O script `script.js` será responsável por atualizar o conteúdo do relógio.

### Descrição do CSS:
- O `body` usa o Flexbox para centralizar o relógio na tela, com fundo escuro e uma fonte limpa.
- O `#clock` tem um fundo branco, bordas arredondadas e uma sombra para destacar o elemento.
- O `#time` tem uma grande fonte centralizada para exibir a hora de forma destacada.

### Descrição do JavaScript
- A função `updateTime()` captura o tempo atual usando o objeto `Date`, formata as horas, minutos e segundos para garantir que sempre apareçam com dois dígitos e, em seguida, exibe a hora na `div` com o id `time`.
- `setInterval(updateTime, 1000)` chama a função `updateTime()` a cada 1000 milissegundos (1 segundo), garantindo que o relógio seja atualizado em tempo real.
- `updateTime()` também é chamada imediatamente para mostrar o horário correto ao carregar a página.

## 📜 Licença:
Este projeto é livre para uso e modificação. <br>
Esse projeto foi desenvolvido a partir de uma aula no Youtube, para fins de prática de código.

Link: https://relogio-digital-css.netlify.app/

### Responsividade Desktop:
<img src="/readme/responsividade-desktop.png" width="720px">

### Responsividade Mobile:
<img src="/readme/android.jpg" width="480px">