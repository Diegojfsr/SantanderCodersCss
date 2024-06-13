
Seletores, responsividade e animações

Seletores Extras
Basico de Responsividade
Outras Propriedades
- opacity
- visibility
- transform
Animacao
- @keyframes
- propriedades
- animation-name
- animation-duration
- animation-delay
- animation-iteration-count
- animation-direction
- animation-fill-mode
- animation-play-state
Exemplo Animacao de Carregamento
Performance das animacoes
Animando o hover




Seletores
- id(#)
- classe(.)
- data-atributes[data-company=""]

Responsividade
- @media screen
- @media print

- display: none
- visibility: hidden
- opacity: .0
- transform: scale(1.5) rotate(30deg) translateY(3rem)
- transition: .2s ease-in-out
- transition: background-color 1s ease-in-out



Exemplos:

Responsividade

@media print { 
    .bg {
            display: none; 
        } 
}

 @media screen and (min-width: 1000px ) and (max-width: 999px) { 
    .bg {
            height: 45vh
        } 
}


Animacao

[data-anchor=""]:hover {
    background-color: aqua;
    color: #fff;
    transform: scale(1.2);
}

[data-anchor=""]{
    margin-top: 2rem;
    animation: pulse .5s infinite;
    transform: scale(1);
}

@keyframes pulse {
    0% {
        transform: scale(1);
        opacity: 1;
    }
    50% {
        transform: scale(1.35);
        opacity: 6;
    }
    100% {
        transform: scale(1.35);
        opacity: .6;
    }
}


[data-anchor=""]{
    margin-top: 2rem;
    animation: pulse .5s infinite;
    animation-fil-mode:forwards;
    animation-direction: alternate;
    transform: scale(1);
}

@keyframes pulse {
    0% {
        transform: scale(1);
        opacity: 1;
    }
    100% {
        transform: scale(1.35);
        opacity: 6;
    }
}


