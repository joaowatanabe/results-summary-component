# Frontend Mentor - Solução para o componente de resumo de resultados

Esta é uma solução para o [desafio do componente de resumo de resultados no Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Os desafios do Frontend Mentor ajudam a aprimorar suas habilidades de codificação ao construir projetos realistas.

## Índice

- [Visão Geral](#visão-geral)
  - [O desafio](#o-desafio)
  - [Capturas de tela](#capturas-de-tela)
  - [Links](#links)
- [Meu Processo](#meu-processo)
  - [Tecnologias utilizadas](#tecnologias-utilizadas)
  - [O que eu aprendi](#o-que-eu-aprendi)
  - [Desenvolvimento contínuo](#desenvolvimento-contínuo)
  - [Recursos úteis](#recursos-úteis)
- [Autor](#autor)
- [Agradecimentos](#agradecimentos)

## Visão Geral

### O desafio

Os usuários devem ser capazes de:

- Visualizar o layout ideal da interface, dependendo do tamanho da tela do dispositivo
- Ver os estados de hover e focus para todos os elementos interativos da página

### Capturas de tela

![Web](result-summary-component/assets/screenshots/gif/web.gif)
![Mobile](result-summary-component/assets/screenshots/gif/mobile.gif)

### Links

- URL da solução: [Frontend Mentor](https://www.frontendmentor.io/solutions/results-summary-component-solution-with-animated-button-h9FaWOrDd6)

## Meu Processo

### Tecnologias utilizadas

- HTML5 semântico
- Propriedades customizadas de CSS
- Flexbox
- CSS Grid

### O que eu aprendi

Este é o segundo desafio que resolvo e estou orgulhoso de mim mesmo. É importante celebrar pequenas conquistas.

Aprendi algumas coisas novas em CSS:

```css
@keyframes anima {
  0% {
    transform: scale(1);
  }
  100% {
    transform: scale(1.03);
  }
}

.btn:hover {
  background-image: linear-gradient(hsla(256, 72%, 46%, 1), hsl(241, 81%, 54%));
  animation-name: anima;
  animation-duration: 0.7s;
  animation-timing-function: ease-in-out;
  animation-iteration-count: infinite;
  animation-direction: alternate;
}
```

### Desenvolvimento contínuo

Os desafios têm me ajudado bastante, incentivando-me a continuar praticando, experimentando coisas novas e observando as coisas de uma nova perspectiva. Quero seguir estudando CSS e começar a explorar mais o JavaScript. Também tenho interesse em começar a utilizar alguns frameworks.

### Recursos úteis

- [Vídeo tutorial sobre Box Shadow - PT-BR](https://www.youtube.com/watch?v=xrftarUZl44&t=302s&ab_channel=dpw) - Este vídeo me ajudou a entender melhor como utilizar o Box Shadow no CSS.

## Autor

- Frontend Mentor - João Vicente Watanabe [@joaowatanabe](https://www.frontendmentor.io/profile/joaowatanabe)
- Twitter - [@wabemusic](https://www.twitter.com/wabemusic)
