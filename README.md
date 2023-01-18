# HZC-2023
Esse projeto foi desenvolvido com os conhecimentos que adquiri nas aulas de CSS sobre Flexbox e Grid da Alura.
<br>
<br>
<div>
<img alt="imagem curso de CSS - flexbox e grid" src="https://github.com/Feuchard/HZC-2023/blob/main/assets/img/css-flexbox-grid.png">
<br>
<br>
  <ul>
      <li>Relacione o flexbox com maneiras já conhecidas de posicionamento de elementos</li>
      <li>Veja o flexbox e suas propriedades para o posicionamento de elementos</li>
      <li>Produza o cabeçalho utilizando as ferramentas do flexbox</li>
      <li>Identifique as limitações do flexbox</li>
      <li>Diferencie o flexbox do grid</li>
      <li>Prototipe o layout de um cartão utilizando propriedades básicas do grid</li>
      <li>Reconheça no layout do figma o que pode fazer parte de um grid</li>
      <li>Associe as propriedades novas com o que já existe de estrutura no projeto</li>
      <li>Veja como o layout atual se comporta em um dispositivo diferente</li>
      <li>Resolva os problemas com novas propriedades de grid</li>
      <li>Produza o restante do layout com novas propriedades de grid</li>
      <li>Identifique problemas como: repetição de código, manutenção e unidades de medida</li>
      <li>Entenda as vantagens de se utilizar a abordagem do grid</li>
      <li>Planeje como pode ser a construção das outras páginas do projeto utilizando as técnicas aprendidas</li>
    </ul>
</div>  
 
## Visualize o projeto
  
  <ul>
    <li><a href="https://feuchard.github.io/HZC-2023/" target="_blank">HZC - 2023</li
</ul>
<br>
        
##       
        
# Guia de estilos

Toda a estilização que será usada no projeto dentro do figma.

[Link do projeto no figma](https://www.figma.com/file/ibWktwVpnog76rMYOdVhks/Dispondo-elementos-com-flexbox-e-grid?node-id=54%3A2358)

## Fonte

```html
Open Sans:
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap">
```

## Cores

corpo: `#1D232A`

cabeçalho: `#1D232A`

cabeçalho mobile: `#15191C`

menu lateral: `#15191C`

cartão: `#2C343A`

fonte: `#FFFFFF`

fonte alternativa: `#95999C`

links: `#0480DC`

botão: `#0480DC`

sombras: `0px 4px 4px rgba(0, 0, 0, 0.16)`

## Ícones

Estão dentro do arquivo de fonte `icones.ttf`. Para usar, primeiro importe a fonte no projeto usando `@font-face` e depois utilize os códigos abaixo para exibir o ícone.

```css
@font-face {
    font-family: 'icones';
    src: url(../font/icones.ttf);
}
```

> Cuidado com a localização do arquivo `icones.ttf`

Camisas = `\e900`

Carrinho = `\e901`

Inicio = `\e902`

Integrantes = `\e903`

Menu = `\e904`

Moeda = `\e905`

Notificação = `\e906`

Pico = `\e908`

Picos = `\e909`

Pinturas = `\e90a`

Play = `\e90b`

Relogio = `\e90c`

Seta-baixo = `\e90d`

Videos = `\e90e`

Visualizacao = `\e90f`

## Espaçamentos

Espaço interno botão: `8px`

Espaço entre elementos do botão: `8px`

Espaço entre elementos: `16px/8px`

Espaçamento interno do corpo: `16px`

Espaçamento entre o título do cartão de recentes e seus itens: `24px`

## Tamanhos

Tamanho do dispositivo mobile: `360px`

Tamanho do dispositivo desktop: `1440px`

Largura máxima do conteúdo principal: `1120px`

Largura máxima de um cartão desktop: `256px`

Altura mínima de um cartão: `320px`
