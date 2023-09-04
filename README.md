**Avaliação 01 de Desenvolvimento Web**

Este repositório contem a Avaliação 01 da disciplina de Desenvolvimento Web, na qual foi desenvolvida uma página responsiva para quatro tamanhos de tela diferentes: 1366px, 768px, 450px e 320px. 

**Descrição do Projeto**
O objetivo desta avaliação foi aplicar os conceitos aprendidos ao longo do primeiro mês da disciplina de Desenvolvimento Web.
O desafio era criar uma página que se adaptasse a quatro tamanhos de tela diferentes, demonstrando o uso de métodos como Flexbox e Grid Layout.

**Instruções de Uso**
Para visualizar a página responsiva, siga estas instruções:

  - Clone ou faça o download deste repositório para o seu computador.
  - Abra o arquivo index.html em um navegador da web.
  - Redimensione a janela do navegador para os tamanhos de tela desejados (1366px, 768px, 450px, 320px) para ver como a página se adapta.
Você poderá visualizar a página também através do link: https://anacschmitz.github.io/avaliacao01/

**Exemplos e Capturas de Tela**
Aqui estão os exemplos da página em diferentes tamanhos de tela:

Tela de 1366px 1366px:
![1366](https://github.com/anacschmitz/avaliacao01/blob/main/layout/1366.png)

Tela de 768px 768px:
![768px](https://github.com/anacschmitz/avaliacao01/blob/main/layout/768.png)

Tela de 450px 450px:
![450px](https://github.com/anacschmitz/avaliacao01/blob/main/layout/450.png)

Tela de 320px 320px:
![320px](https://github.com/anacschmitz/avaliacao01/blob/main/layout/320.png)

**Tecnologias Utilizadas:**
Nesta avaliação, foram utilizadas as seguintes tecnologias e ferramentas:

 - HTML
 - CSS
 - IDE: VsCode

Para tornar a página responsiva, foram aplicadas as regras de consulta de mídia(@media):

  -  Para utilizar essa regra você deve especificar uma consulta de mídia, que é um conjunto de condições que devem ser atendidas para que as regras de estilo dentro do bloco @media sejam aplicadas.
  -  Dentro do bloco @media, você pode colocar todas as regras de estilo que deseja aplicar quando as condições especificadas forem verdadeiras.
  -  O exemplo abaixo mostra uma condição de alteração de cor de fundo quando a tela a ser utilizada atingir uma largura de 768px.

```
@media (max-width: 768px) {
  body {
    back-ground-color: red;
  }
} ```
