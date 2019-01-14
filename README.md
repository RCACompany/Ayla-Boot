@charset  " UTF-8 " ;

/ * !
 * animate.css -http: //daneden.me/animate
 * Versão - 3.5.2
 * Licenciado sob a licença do MIT - http://opensource.org/licenses/MIT
 *
 * Copyright (c) 2017 Daniel Eden
 * /

.animated {
  duração da animação : 1 s ;
  animação-fill-mode : ambos ;
}

.animated.infinite {
  animation-iteration-count : infinito ;
}

.animated.hinge {
  animação-duração : 2 s ;
}

.animated.flipOutX ,
.animated.flipOutY ,
.animated.bounceIn ,
.animated.bounceOut {
  animação-duração : 0,75 s ;
}

@keyframes  bounce {
  a partir de , 20% , 53% , 80% , de {
    função de temporização de animação : cubic-bezier ( 0.215 , 0.610 , 0.355 , 1.000 );
    transform : translate3d ( 0 , 0 , 0 );
  }

  40% , 43% {
    função de temporização de animação : cubic-bezier ( 0,755 , 0,050 , 0,855 , 0,060 );
    transformar : translate3d ( 0 , -30 px , 0 );
  }

  70% {
    função de temporização de animação : cubic-bezier ( 0,755 , 0,050 , 0,855 , 0,060 );
    transformar : translate3d ( 0 , -15 px , 0 );
  }

  90% {
    transformar : translate3d ( 0 , -4 px , 0 );
  }
}

.bounce {
  nome da animação : salto;
  transformação-origem : fundo do centro  ;
}

@keyframes  flash {
  de , 50% , para {
    opacidade : 1 ;
  }

  25% , 75% {
    opacidade : 0 ;
  }
}

.flash {
  nome da animação : flash;
}

/ * originalmente de autoria de Nick Pettit - https://github.com/nickpettit/glide * /

@keyframes  pulse {
  de {
    transformar : escala3d ( 1 , 1 , 1 );
  }

  50% {
    transformar : escala3d ( 1,05 , 1,05 , 1,05 );
  }

  para {
    transformar : escala3d ( 1 , 1 , 1 );
  }
}

.pulse {
  nome da animação : pulso;
}

@keyframes  rubberBand {
  de {
    transformar : escala3d ( 1 , 1 , 1 );
  }

  30% {
    transformar : escala3d ( 1,25 , 0,75 , 1 );
  }

  40% {
    transformar : escala3d ( 0,75 , 1,25 , 1 );
  }

  50% {
    transformar : escala3d ( 1,15 , 0,85 , 1 );
  }

  65% {
    transform : scale3d ( 0,95 , 1,05 , 1 );
  }

  75% {
    transformar : escala3d ( 1,05 , 0,95 , 1 );
  }

  para {
    transformar : escala3d ( 1 , 1 , 1 );
  }
}

.rubberBand {
  nome da animação : rubberBand;
}

@keyframes  shake {
  de , para {
    transform : translate3d ( 0 , 0 , 0 );
  }

  10% , 30% , 50% , 70% , 90% {
    transformar : translate3d ( -10 px , 0 , 0 );
  }

  20% , 40% , 60% , 80% {
    transformar : translate3d ( 10 px , 0 , 0 );
  }
}

.shake {
  nome da animação : agitar;
}

@keyframes  headShake {
  0% {
    transformar : translateX ( 0 );
  }

  6,5% {
    transformar : translateX ( -6 px ) rotateY ( -9 graus );
  }

  18,5% {
    transformar : translateX ( 5 px ) rotateY ( 7 graus );
  }

  31,5% {
    transformar : translateX ( -3 px ) rotateY ( -5 graus );
  }

  43,5% {
    transformar : translateX ( 2 px ) rotateY ( 3 graus );
  }

  50% {
    transformar : translateX ( 0 );
  }
}

.headShake {
  função de temporização de animação : facilidade-out-out ;
  nome da animação : headShake;
}

@keyframes  swing {
  20% {
    transformar : rotate3d ( 0 , 0 , 1 , 15 graus );
  }

  40% {
    transformar : rotate3d ( 0 , 0 , 1 , -10 graus );
  }

  60% {
    transformar : rotate3d ( 0 , 0 , 1 , 5 graus );
  }

  80% {
    transformar : rotate3d ( 0 , 0 , 1 , -5 graus );
  }

  para {
    transformar : rotate3d ( 0 , 0 , 1 , 0 deg );
  }
}

.swing {
  transformação-origem : centro superior  ;
  nome da animação : swing;
}

@keyframes  tada {
  de {
    transformar : escala3d ( 1 , 1 , 1 );
  }

  10% , 20% {
    transformar : escala3d ( 0,9 , 0,9 , 0,9 ) rotate3d ( 0 , 0 , 1 , -3 graus );
  }

  30% , 50% , 70% , 90% {
    transformar : scale3d ( 1,1 , 1,1 , 1,1 ) rotate3d ( 0 , 0 , 1 , 3 deg );
  }

  40% , 60% , 80% {
    transformar : escala3d ( 1,1 , 1,1 , 1,1 ) rotate3d ( 0 , 0 , 1 , -3 graus );
  }

  para {
    transformar : escala3d ( 1 , 1 , 1 );
  }
}

.tada {
  nome da animação : tada;
}

/ * originalmente de autoria de Nick Pettit - https://github.com/nickpettit/glide * /

@keyframes  wobble {
  de {
    transformar : nenhum ;
  }

  15% {
    transformar : translate3d ( -25 % , 0 , 0 ) rotate3d ( 0 , 0 , 1 , -5 graus );
  }

  30% {
    transformar : translate3d ( 20 % , 0 , 0 ) rotate3d ( 0 , 0 , 1 , 3 graus );
  }

  45% {
    transformar : translate3d ( -15 % , 0 , 0 ) rotate3d ( 0 , 0 , 1 , -3 graus );
  }

  60% {
    transformar : translate3d ( 10 % , 0 , 0 ) rotate3d ( 0 , 0 , 1 , 2 deg );
  }

  75% {
    transformar : translate3d ( -5 % , 0 , 0 ) rotate3d ( 0 , 0 , 1 , -1 deg );
  }

  para {
    transformar : nenhum ;
  }
}

.wobble {
  nome da animação : wobble;
}

@keyframes  jello {
  de , 11,1% , para {
    transformar : nenhum ;
  }

  22,2% {
    transformar : skewX ( -12,5 ° C ) skewY ( -12,5 ° C );
  }

  33,3% {
    transformar : skewX ( 6,25 graus ) skewY ( 6,25 graus );
  }

  44,4% {
    transformar : skewX ( -3.125 graus ) skewY ( -3,125 graus );
  }

  55,5% {
    transformar : skewX ( 1,5625 graus ) skewY ( 1,5625 graus );
  }

  66,6% {
    transformar : skewX ( -0,78125 graus ) skewY ( -0,78125 graus );
  }

  77,7% {
    transformar : skewX ( 0,390625 graus ) skewY ( 0,390625 graus );
  }

  88,8% {
    transformar : skewX ( -0,1953125 graus ) skewY ( -0,1953125 graus );
  }
}

.jello {
  nome da animação : jello;
  transformar-origem : centro ;
}

@keyframes  bounceIn {
  a partir de , 20% , 40% , 60% , 80% , de {
    função de temporização de animação : cubic-bezier ( 0.215 , 0.610 , 0.355 , 1.000 );
  }

  0% {
    opacidade : 0 ;
    Transformar : escala3d ( .3 , .3 , .3 );
  }

  20% {
    transform : scale3d ( 1.1 , 1.1 , 1.1 );
  }

  40% {
    transformar : escala3d ( 0,9 , 0,9 , 0,9 );
  }

  60% {
    opacidade : 1 ;
    transform : scale3d ( 1,03 , 1,03 , 1,03 );
  }

  80% {
    transformar : scale3d ( 0,97 , 0,97 , 0,97 );
  }

  para {
    opacidade : 1 ;
    transformar : escala3d ( 1 , 1 , 1 );
  }
}

.bounceIn {
  nome da animação : bounceIn;
}

@keyframes  bounceInDown {
  de , 60% , 75% , 90% , para {
    função de temporização de animação : cubic-bezier ( 0.215 , 0.610 , 0.355 , 1.000 );
  }

  0% {
    opacidade : 0 ;
    transformar : translate3d ( 0 , -3000 px , 0 );
  }

  60% {
    opacidade : 1 ;
    transformar : translate3d ( 0 , 25 px , 0 );
  }

  75% {
    transformar : translate3d ( 0 , -10 px , 0 );
  }

  90% {
    transformar : translate3d ( 0 , 5 px , 0 );
  }

  para {
    transformar : nenhum ;
  }
}

.bounceInDown {
  nome da animação : bounceInDown;
}

@keyframes  bounceInLeft {
  de , 60% , 75% , 90% , para {
    função de temporização de animação : cubic-bezier ( 0.215 , 0.610 , 0.355 , 1.000 );
  }

  0% {
    opacidade : 0 ;
    transformar : translate3d ( -3000 px , 0 , 0 );
  }

  60% {
    opacidade : 1 ;
    transformar : translate3d ( 25 px , 0 , 0 );
  }

  75% {
    transformar : translate3d ( -10 px , 0 , 0 );
  }

  90% {
    transformar : translate3d ( 5 px , 0 , 0 );
  }

  para {
    transformar : nenhum ;
  }
}

.bounceInLeft {
  nome da animação : bounceInLeft;
}

@keyframes  bounceInRight {
  de , 60% , 75% , 90% , para {
    função de temporização de animação : cubic-bezier ( 0.215 , 0.610 , 0.355 , 1.000 );
  }

  de {
    opacidade : 0 ;
    transformar : translate3d ( 3000 px , 0 , 0 );
  }

  60% {
    opacidade : 1 ;
    transformar : translate3d ( -25 px , 0 , 0 );
  }

  75% {
    transformar : translate3d ( 10 px , 0 , 0 );
  }

  90% {
    transformar : translate3d ( -5 px , 0 , 0 );
  }

  para {
    transformar : nenhum ;
  }
}

.bounceInRight {
  nome da animação : bounceInRight;
}

@keyframes  bounceInUp {
  de , 60% , 75% , 90% , para {
    função de temporização de animação : cubic-bezier ( 0.215 , 0.610 , 0.355 , 1.000 );
  }

  de {
    opacidade : 0 ;
    transformar : translate3d ( 0 , 3000 px , 0 );
  }

  60% {
    opacidade : 1 ;
    transformar : translate3d ( 0 , -20 px , 0 );
  }

  75% {
    transformar : translate3d ( 0 , 10 px , 0 );
  }

  90% {
    transformar : translate3d ( 0 , -5 px , 0 );
  }

  para {
    transform : translate3d ( 0 , 0 , 0 );
  }
}

.bounceInUp {
  nome da animação : bounceInUp;
}

@keyframes  bounceOut {
  20% {
    transformar : escala3d ( 0,9 , 0,9 , 0,9 );
  }

  50% , 55% {
    opacidade : 1 ;
    transform : scale3d ( 1.1 , 1.1 , 1.1 );
  }

  para {
    opacidade : 0 ;
    Transformar : escala3d ( .3 , .3 , .3 );
  }
}

.bounceOut {
  nome da animação : bounceOut;
}

@keyframes  bounceOutDown {
  20% {
    transformar : translate3d ( 0 , 10 px , 0 );
  }

  40% , 45% {
    opacidade : 1 ;
    transformar : translate3d ( 0 , -20 px , 0 );
  }

  para {
    opacidade : 0 ;
    transformar : translate3d ( 0 , 2000 px , 0 );
  }
}

.bounceOutDown {
  nome da animação : bounceOutDown;
}

@keyframes  bounceOutLeft {
  20% {
    opacidade : 1 ;
    transformar : translate3d ( 20 px , 0 , 0 );
  }

  para {
    opacidade : 0 ;
    transformar : translate3d ( -2000 px , 0 , 0 );
  }
}

.bounceOutLeft {
  nome da animação : bounceOutLeft;
}

@keyframes  bounceOutRight {
  20% {
    opacidade : 1 ;
    transformar : translate3d ( -20 px , 0 , 0 );
  }

  para {
    opacidade : 0 ;
    transformar : translate3d ( 2000 px , 0 , 0 );
  }
}

.bounceOutRight {
  nome da animação : bounceOutRight;
}

@keyframes  bounceOutUp {
  20% {
    transformar : translate3d ( 0 , -10 px , 0 );
  }

  40% , 45% {
    opacidade : 1 ;
    transformar : translate3d ( 0 , 20 px , 0 );
  }

  para {
    opacidade : 0 ;
    transformar : translate3d ( 0 , -2000 px , 0 );
  }
}

.bounceOutUp {
  nome da animação : bounceOutUp;
}

@keyframes  fadeIn {
  de {
    opacidade : 0 ;
  }

  para {
    opacidade : 1 ;
  }
}

.fadeIn {
  nome da animação : fadeIn;
}

@keyframes  fadeInDown {
  de {
    opacidade : 0 ;
    transformar : translate3d ( 0 , -100 % , 0 );
  }

  para {
    opacidade : 1 ;
    transformar : nenhum ;
  }
}

.fadeInDown {
  nome da animação : fadeInDown;
}

@keyframes  fadeInDownBig {
  de {
    opacidade : 0 ;
    transformar : translate3d ( 0 , -2000 px , 0 );
  }

  para {
    opacidade : 1 ;
    transformar : nenhum ;
  }
}

.fadeInDownBig {
  nome da animação : fadeInDownBig;
}

@keyframes  fadeInLeft {
  de {
    opacidade : 0 ;
    transform : translate3d ( -100 % , 0 , 0 );
  }

  para {
    opacidade : 1 ;
    transformar : nenhum ;
  }
}

.fadeInLeft {
  nome da animação : fadeInLeft;
}

@keyframes  fadeInLeftBig {
  de {
    opacidade : 0 ;
    transformar : translate3d ( -2000 px , 0 , 0 );
  }

  para {
    opacidade : 1 ;
    transformar : nenhum ;
  }
}

.fadeInLeftBig {
  nome da animação : fadeInLeftBig;
}

@keyframes  fadeInRight {
  de {
    opacidade : 0 ;
    transform : translate3d ( 100 % , 0 , 0 );
  }

  para {
    opacidade : 1 ;
    transformar : nenhum ;
  }
}

.fadeInRight {
  nome da animação : fadeInRight;
}

@keyframes  fadeInRightBig {
  de {
    opacidade : 0 ;
    transformar : translate3d ( 2000 px , 0 , 0 );
  }

  para {
    opacidade : 1 ;
    transformar : nenhum ;
  }
}

.fadeInRightBig {
  nome da animação : fadeInRightBig;
}

@keyframes  fadeInUp {
  de {
    opacidade : 0 ;
    transformar : translate3d ( 0 , 100 % , 0 );
  }

  para {
    opacidade : 1 ;
    transformar : nenhum ;
  }
}

.fadeInUp {
  nome da animação : fadeInUp;
}

@keyframes  fadeInUpBig {
  de {
    opacidade : 0 ;
    transformar : translate3d ( 0 , 2000 px , 0 );
  }

  para {
    opacidade : 1 ;
    transformar : nenhum ;
  }
}

.fadeInUpBig {
  nome da animação : fadeInUpBig;
}

@keyframes  fadeOut {
  de {
    opacidade : 1 ;
  }

  para {
    opacidade : 0 ;
  }
}

.fadeOut {
  nome da animação : fadeOut;
}

@keyframes  fadeOutDown {
  de {
    opacidade : 1 ;
  }

  para {
    opacidade : 0 ;
    transformar : translate3d ( 0 , 100 % , 0 );
  }
}

.fadeOutDown {
  nome da animação : fadeOutDown;
}

@keyframes  fadeOutDownBig {
  de {
    opacidade : 1 ;
  }

  para {
    opacidade : 0 ;
    transformar : translate3d ( 0 , 2000 px , 0 );
  }
}

.fadeOutDownBig {
  nome da animação : fadeOutDownBig;
}

@keyframes  fadeOutLeft {
  de {
    opacidade : 1 ;
  }

  para {
    opacidade : 0 ;
    transform : translate3d ( -100 % , 0 , 0 );
  }
}

.fadeOutLeft {
  nome da animação : fadeOutLeft;
}

@keyframes  fadeOutLeftBig {
  de {
    opacidade : 1 ;
  }

  para {
    opacidade : 0 ;
    transformar : translate3d ( -2000 px , 0 , 0 );
  }
}

.fadeOutLeftBig {
  nome da animação : fadeOutLeftBig;
}

@keyframes  fadeOutRight {
  de {
    opacidade : 1 ;
  }

  para {
    opacidade : 0 ;
    transform : translate3d ( 100 % , 0 , 0 );
  }
}

.fadeOutRight {
  nome da animação : fadeOutRight;
}

@keyframes  fadeOutRightBig {
  de {
    opacidade : 1 ;
  }

  para {
    opacidade : 0 ;
    transformar : translate3d ( 2000 px , 0 , 0 );
  }
}

.fadeOutRightBig {
  nome da animação : fadeOutRightBig;
}

@keyframes  fadeOutUp {
  de {
    opacidade : 1 ;
  }

  para {
    opacidade : 0 ;
    transformar : translate3d ( 0 , -100 % , 0 );
  }
}

.fadeOutUp {
  nome da animação : fadeOutUp;
}

@keyframes  fadeOutUpBig {
  de {
    opacidade : 1 ;
  }

  para {
    opacidade : 0 ;
    transformar : translate3d ( 0 , -2000 px , 0 );
  }
}

.fadeOutUpBig {
  nome da animação : fadeOutUpBig;
}

@keyframes  flip {
  de {
    transformar : perspectiva ( 400 px ) rotate3d ( 0 , 1 , 0 , -360 graus );
    função de temporização de animação : facilidade de saída ;
  }

  40% {
    transformar : perspectiva ( 400 px ) translate3d ( 0 , 0 , 150 px ) rotate3d ( 0 , 1 , 0 , -190 graus );
    função de temporização de animação : facilidade de saída ;
  }

  50% {
    transformar : perspectiva ( 400 px ) translate3d ( 0 , 0 , 150 px ) rotate3d ( 0 , 1 , 0 , -170 graus );
    função de temporização de animação : facilidade de entrada ;
  }

  80% {
    transformar : perspectiva ( 400 px ) escala3d ( 0,95 , 0,95 , 0,95 );
    função de temporização de animação : facilidade de entrada ;
  }

  para {
    transformar : perspectiva ( 400 px );
    função de temporização de animação : facilidade de entrada ;
  }
}

.animated.flip {
  -webkit-backface-visibility : visível ;
  backface-visibility : visível ;
  nome da animação : flip ;
}

@keyframes  flipInX {
  de {
    transformar : perspectiva ( 400 px ) rotate3d ( 1 , 0 , 0 , 90 graus );
    função de temporização de animação : facilidade de entrada ;
    opacidade : 0 ;
  }

  40% {
    transformar : perspectiva ( 400 px ) rotate3d ( 1 , 0 , 0 , -20 graus );
    função de temporização de animação : facilidade de entrada ;
  }

  60% {
    transformar : perspectiva ( 400 px ) rotate3d ( 1 , 0 , 0 , 10 graus );
    opacidade : 1 ;
  }

  80% {
    transformar : perspectiva ( 400 px ) rotate3d ( 1 , 0 , 0 , -5 graus );
  }

  para {
    transformar : perspectiva ( 400 px );
  }
}

.flipInX {
  -webkit-backface-visibility : visível  ! importante ;
  backface-visibility : visível  ! importante ;
  nome da animação : flipInX;
}

@keyframes  flipInY {
  de {
    transformar : perspectiva ( 400 px ) rotate3d ( 0 , 1 , 0 , 90 graus );
    função de temporização de animação : facilidade de entrada ;
    opacidade : 0 ;
  }

  40% {
    transformar : perspectiva ( 400 px ) rotate3d ( 0 , 1 , 0 , -20 graus );
    função de temporização de animação : facilidade de entrada ;
  }

  60% {
    transformar : perspectiva ( 400 px ) rotate3d ( 0 , 1 , 0 , 10 graus );
    opacidade : 1 ;
  }

  80% {
    transformar : perspectiva ( 400 px ) rotate3d ( 0 , 1 , 0 , -5 graus );
  }

  para {
    transformar : perspectiva ( 400 px );
  }
}

.flipInY {
  -webkit-backface-visibility : visível  ! importante ;
  backface-visibility : visível  ! importante ;
  nome da animação : flipInY;
}

@keyframes  flipOutX {
  de {
    transformar : perspectiva ( 400 px );
  }

  30% {
    transformar : perspectiva ( 400 px ) rotate3d ( 1 , 0 , 0 , -20 graus );
    opacidade : 1 ;
  }

  para {
    transformar : perspectiva ( 400 px ) rotate3d ( 1 , 0 , 0 , 90 graus );
    opacidade : 0 ;
  }
}

.flipOutX {
  nome da animação : flipOutX;
  -webkit-backface-visibility : visível  ! importante ;
  backface-visibility : visível  ! importante ;
}

@keyframes  flipOutY {
  de {
    transformar : perspectiva ( 400 px );
  }

  30% {
    transformar : perspectiva ( 400 px ) rotate3d ( 0 , 1 , 0 , -15 graus );
    opacidade : 1 ;
  }

  para {
    transformar : perspectiva ( 400 px ) rotate3d ( 0 , 1 , 0 , 90 graus );
    opacidade : 0 ;
  }
}

.flipOutY {
  -webkit-backface-visibility : visível  ! importante ;
  backface-visibility : visível  ! importante ;
  nome da animação : flipOutY;
}

@keyframes  lightSpeedIn {
  de {
    transformar : translate3d ( 100 % , 0 , 0 ) skewX ( -30 graus );
    opacidade : 0 ;
  }

  60% {
    transformar : skewX ( 20 graus );
    opacidade : 1 ;
  }

  80% {
    transformar : skewX ( -5 graus );
    opacidade : 1 ;
  }

  para {
    transformar : nenhum ;
    opacidade : 1 ;
  }
}

.lightSpeedIn {
  nome da animação : lightSpeedIn;
  função de temporização de animação : facilidade de saída ;
}

@keyframes  lightSpeedOut {
  de {
    opacidade : 1 ;
  }

  para {
    transformar : translate3d ( 100 % , 0 , 0 ) skewX ( 30 graus );
    opacidade : 0 ;
  }
}

.lightSpeedOut {
  nome da animação : lightSpeedOut;
  função de temporização de animação : facilidade de entrada ;
}

@keyframes  rotateIn {
  de {
    transformar-origem : centro ;
    transformar : rotate3d ( 0 , 0 , 1 , -200 graus );
    opacidade : 0 ;
  }

  para {
    transformar-origem : centro ;
    transformar : nenhum ;
    opacidade : 1 ;
  }
}

.rotateIn {
  nome da animação : rotateIn;
}

@keyframes  rotateInDownLeft {
  de {
    transformação-origem : fundo esquerdo  ;
    transformar : rotate3d ( 0 , 0 , 1 , -45 graus );
    opacidade : 0 ;
  }

  para {
    transformação-origem : fundo esquerdo  ;
    transformar : nenhum ;
    opacidade : 1 ;
  }
}

.rotateInDownLeft {
  nome da animação : rotateInDownLeft;
}

@keyframes  rotateInDownRight {
  de {
    transformar-origem : fundo direito  ;
    transformar : rotate3d ( 0 , 0 , 1 , 45 graus );
    opacidade : 0 ;
  }

  para {
    transformar-origem : fundo direito  ;
    transformar : nenhum ;
    opacidade : 1 ;
  }
}

.rotateInDownRight {
  nome da animação : rotateInDownRight;
}

@keyframes  rotateInUpLeft {
  de {
    transformação-origem : fundo esquerdo  ;
    transformar : rotate3d ( 0 , 0 , 1 , 45 graus );
    opacidade : 0 ;
  }

  para {
    transformação-origem : fundo esquerdo  ;
    transformar : nenhum ;
    opacidade : 1 ;
  }
}

.rotateInUpLeft {
  nome da animação : rotateInUpLeft;
}

@keyframes  rotateInUpRight {
  de {
    transformar-origem : fundo direito  ;
    transformar : rotate3d ( 0 , 0 , 1 , -90 graus );
    opacidade : 0 ;
  }

  para {
    transformar-origem : fundo direito  ;
    transformar : nenhum ;
    opacidade : 1 ;
  }
}

.rotateInUpRight {
  nome da animação : rotateInUpRight;
}

@keyframes  rotateOut {
  de {
    transformar-origem : centro ;
    opacidade : 1 ;
  }

  para {
    transformar-origem : centro ;
    transformar : rotate3d ( 0 , 0 , 1 , 200 graus );
    opacidade : 0 ;
  }
}

.rotateOut {
  nome da animação : rotateOut;
}

@keyframes  rotateOutDownLeft {
  de {
    transformação-origem : fundo esquerdo  ;
    opacidade : 1 ;
  }

  para {
    transformação-origem : fundo esquerdo  ;
    transformar : rotate3d ( 0 , 0 , 1 , 45 graus );
    opacidade : 0 ;
  }
}

.rotateOutDownLeft {
  nome da animação : rotateOutDownLeft;
}

@keyframes  rotateOutDownRight {
  de {
    transformar-origem : fundo direito  ;
    opacidade : 1 ;
  }

  para {
    transformar-origem : fundo direito  ;
    transformar : rotate3d ( 0 , 0 , 1 , -45 graus );
    opacidade : 0 ;
  }
}

.rotateOutDownRight {
  nome da animação : rotateOutDownRight;
}

@keyframes  rotateOutUpLeft {
  de {
    transformação-origem : fundo esquerdo  ;
    opacidade : 1 ;
  }

  para {
    transformação-origem : fundo esquerdo  ;
    transformar : rotate3d ( 0 , 0 , 1 , -45 graus );
    opacidade : 0 ;
  }
}

.rotateOutUpLeft {
  nome da animação : rotateOutUpLeft;
}

@keyframes  rotateOutUpRight {
  de {
    transformar-origem : fundo direito  ;
    opacidade : 1 ;
  }

  para {
    transformar-origem : fundo direito  ;
    transformar : rotate3d ( 0 , 0 , 1 , 90 graus );
    opacidade : 0 ;
  }
}

.rotateOutUpRight {
  nome da animação : rotateOutUpRight;
}

@keyframes  dobradiça {
  0% {
    transformação-origem : canto superior  esquerdo ;
    função de temporização de animação : facilidade-out-out ;
  }

  20% , 60% {
    transformar : rotate3d ( 0 , 0 , 1 , 80 graus );
    transformação-origem : canto superior  esquerdo ;
    função de temporização de animação : facilidade-out-out ;
  }

  40% , 80% {
    transformar : rotate3d ( 0 , 0 , 1 , 60 graus );
    transformação-origem : canto superior  esquerdo ;
    função de temporização de animação : facilidade-out-out ;
    opacidade : 1 ;
  }

  para {
    transformar : translate3d ( 0 , 700 px , 0 );
    opacidade : 0 ;
  }
}

.hinge {
  nome da animação : dobradiça;
}

@keyframes  jackInTheBox {
  de {
    opacidade : 0 ;
    transformar : escala ( 0,1 ) girar ( 30 graus );
    transformação-origem : fundo do centro  ;
  }

  50% {
    transformar : girar ( -10 graus );
  }

  70% {
    transformar : girar ( 3 graus );
  }

  para {
    opacidade : 1 ;
    transformar : escala ( 1 );
  }
}

.jackInTheBox {
  nome da animação : jackInTheBox;
}

/ * originalmente de autoria de Nick Pettit - https://github.com/nickpettit/glide * /

@keyframes  rollIn {
  de {
    opacidade : 0 ;
    transformar : translate3d ( -100 % , 0 , 0 ) rotate3d ( 0 , 0 , 1 , -120 graus );
  }

  para {
    opacidade : 1 ;
    transformar : nenhum ;
  }
}

.rollIn {
  nome da animação : rollIn;
}

/ * originalmente de autoria de Nick Pettit - https://github.com/nickpettit/glide * /

@keyframes  rollOut {
  de {
    opacidade : 1 ;
  }

  para {
    opacidade : 0 ;
    transformar : translate3d ( 100 % , 0 , 0 ) rotate3d ( 0 , 0 , 1 , 120 graus );
  }
}

.rollOut {
  nome da animação : rollOut;
}

@keyframes  zoomIn {
  de {
    opacidade : 0 ;
    Transformar : escala3d ( .3 , .3 , .3 );
  }

  50% {
    opacidade : 1 ;
  }
}

.zoomIn {
  nome da animação : zoomIn;
}

@keyframes  zoomInDown {
  de {
    opacidade : 0 ;
    transform : scale3d ( .1 , .1 , .1 ) translate3d ( 0 , -1000 px , 0 );
    função de temporização de animação : cubic-bezier ( 0,550 , 0,055 , 0,675 , 0,190 );
  }

  60% {
    opacidade : 1 ;
    transformar : escala3d ( 0,475 , 0,475 , 0,475 ) translate3d ( 0 , 60 px , 0 );
    função de temporização de animação : cubic-bezier ( 0,175 , 0,885 , 0,320 , 1 );
  }
}

.zoomInDown {
  nome da animação : zoomInDown;
}

@keyframes  zoomInLeft {
  de {
    opacidade : 0 ;
    transform : scale3d ( .1 , .1 , .1 ) translate3d ( -1000 px , 0 , 0 );
    função de temporização de animação : cubic-bezier ( 0,550 , 0,055 , 0,675 , 0,190 );
  }

  60% {
    opacidade : 1 ;
    transformar : scale3d ( 0,475 , 0,475 , 0,475 ) translate3d ( 10 px , 0 , 0 );
    função de temporização de animação : cubic-bezier ( 0,175 , 0,885 , 0,320 , 1 );
  }
}

.zoomInLeft {
  nome da animação : zoomInLeft;
}

@keyframes  zoomInRight {
  de {
    opacidade : 0 ;
    transform : scale3d ( .1 , .1 , .1 ) translate3d ( 1000 px , 0 , 0 );
    função de temporização de animação : cubic-bezier ( 0,550 , 0,055 , 0,675 , 0,190 );
  }

  60% {
    opacidade : 1 ;
    transform : scale3d ( 0,475 , 0,475 , 0,475 ) translate3d ( -10 px , 0 , 0 );
    função de temporização de animação : cubic-bezier ( 0,175 , 0,885 , 0,320 , 1 );
  }
}

.zoomInRight {
  nome da animação : zoomInRight;
}

@keyframes  zoomInUp {
  de {
    opacidade : 0 ;
    transform : scale3d ( .1 , .1 , .1 ) translate3d ( 0 , 1000 px , 0 );
    função de temporização de animação : cubic-bezier ( 0,550 , 0,055 , 0,675 , 0,190 );
  }

  60% {
    opacidade : 1 ;
    transformar : escala3d ( 0,475 , 0,475 , 0,475 ) translate3d ( 0 , -60 px , 0 );
    função de temporização de animação : cubic-bezier ( 0,175 , 0,885 , 0,320 , 1 );
  }
}

.zoomInUp {
  nome da animação : zoomInUp;
}

@keyframes  zoomOut {
  de {
    opacidade : 1 ;
  }

  50% {
    opacidade : 0 ;
    Transformar : escala3d ( .3 , .3 , .3 );
  }

  para {
    opacidade : 0 ;
  }
}

.zoomOut {
  nome da animação : zoomOut;
}

@keyframes  zoomOutDown {
  40% {
    opacidade : 1 ;
    transformar : escala3d ( 0,475 , 0,475 , 0,475 ) translate3d ( 0 , -60 px , 0 );
    função de temporização de animação : cubic-bezier ( 0,550 , 0,055 , 0,675 , 0,190 );
  }

  para {
    opacidade : 0 ;
    transformar : scale3d ( .1 , .1 , .1 ) translate3d ( 0 , 2000 px , 0 );
    transformação-origem : fundo do centro  ;
    função de temporização de animação : cubic-bezier ( 0,175 , 0,885 , 0,320 , 1 );
  }
}

.zoomOutDown {
  nome da animação : zoomOutDown;
}

@keyframes  zoomOutLeft {
  40% {
    opacidade : 1 ;
    transformar : scale3d ( 0,475 , 0,475 , 0,475 ) translate3d ( 42 px , 0 , 0 );
  }

  para {
    opacidade : 0 ;
    transformar : escala ( .1 ) translate3d ( -2000 px , 0 , 0 );
    transformação-origem : centro esquerdo  ;
  }
}

.zoomOutLeft {
  nome da animação : zoomOutLeft;
}

@keyframes  zoomOutRight {
  40% {
    opacidade : 1 ;
    transform : scale3d ( 0,475 , 0,475 , 0,475 ) translate3d ( -42 px , 0 , 0 );
  }

  para {
    opacidade : 0 ;
    transformar : escala ( .1 ) translate3d ( 2000 px , 0 , 0 );
    transformação-origem : centro direito  ;
  }
}

.zoomOutRight {
  nome da animação : zoomOutRight;
}

@keyframes  zoomOutUp {
  40% {
    opacidade : 1 ;
    transformar : escala3d ( 0,475 , 0,475 , 0,475 ) translate3d ( 0 , 60 px , 0 );
    função de temporização de animação : cubic-bezier ( 0,550 , 0,055 , 0,675 , 0,190 );
  }

  para {
    opacidade : 0 ;
    transform : scale3d ( .1 , .1 , .1 ) translate3d ( 0 , -2000 px , 0 );
    transformação-origem : fundo do centro  ;
    função de temporização de animação : cubic-bezier ( 0,175 , 0,885 , 0,320 , 1 );
  }
}

.zoomOutUp {
  nome da animação : zoomOutUp;
}

@keyframes  slideInDown {
  de {
    transformar : translate3d ( 0 , -100 % , 0 );
    visibilidade : visível ;
  }

  para {
    transform : translate3d ( 0 , 0 , 0 );
  }
}

.slideInDown {
  nome da animação : slideInDown;
}

@keyframes  slideInLeft {
  de {
    transform : translate3d ( -100 % , 0 , 0 );
    visibilidade : visível ;
  }

  para {
    transform : translate3d ( 0 , 0 , 0 );
  }
}

.slideInLeft {
  nome da animação : slideInLeft;
}

@keyframes  slideInRight {
  de {
    transform : translate3d ( 100 % , 0 , 0 );
    visibilidade : visível ;
  }

  para {
    transform : translate3d ( 0 , 0 , 0 );
  }
}

.slideInRight {
  nome da animação : slideInRight;
}

@keyframes  slideInUp {
  de {
    transformar : translate3d ( 0 , 100 % , 0 );
    visibilidade : visível ;
  }

  para {
    transform : translate3d ( 0 , 0 , 0 );
  }
}

.slideInUp {
  nome da animação : slideInUp;
}

@keyframes  slideOutDown {
  de {
    transform : translate3d ( 0 , 0 , 0 );
  }

  para {
    visibilidade : oculto ;
    transformar : translate3d ( 0 , 100 % , 0 );
  }
}

.slideOutDown {
  nome da animação : slideOutDown;
}

@keyframes  slideOutLeft {
  de {
    transform : translate3d ( 0 , 0 , 0 );
  }

  para {
    visibilidade : oculto ;
    transform : translate3d ( -100 % , 0 , 0 );
  }
}

.slideOutLeft {
  nome da animação : slideOutLeft;
}

@keyframes  slideOutRight {
  de {
    transform : translate3d ( 0 , 0 , 0 );
  }

  para {
    visibilidade : oculto ;
    transform : translate3d ( 100 % , 0 , 0 );
  }
}

.slideOutRight {
  nome da animação : slideOutRight;
}

@keyframes  slideOutUp {
  de {
    transform : translate3d ( 0 , 0 , 0 );
  }

  para {
    visibilidade : oculto ;
    transformar : translate3d ( 0 , -100 % , 0 );
  }
}

.slideOutUp {
  nome da animação : slideOutUp;
}

































# Ayla-Boot
[![Build Status](https://travis-ci.org/RCACompany/Ayla-Boot.svg?branch=master)](https://travis-ci.org/RCACompany/Ayla-Boot)
