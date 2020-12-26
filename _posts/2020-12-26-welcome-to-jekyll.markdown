---
layout: post
title:  "Apresentações simples e chamativas com Rmarkdown e ioslides"
date:   2020-12-26 07:28:13 -0300
categories: Rmarkdown R Rstudio ioslides Data-visualization
---

Se você é familiar com o Rmarkdown, mesmo que só um pouco, esse texto é para você! Mostrarei como usar o **ioslides** para suas apresentações, uma alternativa bem interessante para o Microsoft PowerPoint ou Google Presentations. No final do post você será capaz de fazer seus próprios slides e não vai querer saber de outra ferramenta.

O maior diferencial do ioslides é apresentar gráficos e fórmulas geradas pelo seu código R sem precisar exportar a todo momento tabelas e imagens. Isso é feito sem usar uma interface gráfica, tudo no ioslides é escrito por meio da linguagem **markdown**. Caso você não conheça essa linguagem, pode respirar de alívio, em menos de 10 minutos é possível aprender os comandos básicos e começar a escrever. Usando o markdown podemos mudar a fonte do texto, inserir títulos, imagens, links, ajustar a velocidade de transição dos slides e muito mais! Só não esqueça que o propósito dessa ferramenta é facilitar a apresentação de suas análises, se você não tem gráficos ou tabelas criadas no Rstudio, talvez seja melhor usar os métodos mais tradicionais.

Só para se ter uma ideia do que o ioslides é capaz, dá uma olhada nessa [apresentação](https://rpubs.com/Edumangabeira/645422) que fiz com um colega para um trabalho da faculdade.

[Essa aqui também ficou bem interessante](https://rpubs.com/Edumangabeira/687807).

Apesar de alguns problemas aqui e ali(como os links saindo dos slides na última apresentação), não tem nada que não possa ser ajustado e é bem rápido configurar o ioslides, então vamos em frente!

- O único pré-requisito é ter o Rmarkdown instalado. Caso você não tenha, abra o Rstudio e digite no console:

```install.packages('rmarkdown')```

- Concluído este passo com sucesso, reinicie o Rstudio e crie um novo um novo arquivo no formato Rmarkdown. Para isso clique em ```File > New File > Rmarkdown...```

![novo arquivo](/assets/newrmd.png)

- Um pop-up vai surgir na sua tela, selecione "presentation" e clique na opção "HTML (ioslides)".

![](/assets/ionew.png)

- E pronto! Você já pode começar a editar o seu arquivo e criar uma apresentação. O próprio Rstudio fornece um template com alguns exemplos do que é possível fazer usando o ioslides. Para compilar, basta pressionar ```Ctrl+Shift+k```.

![](/assets/exrio.png)

![](/assets/tableio.png)

![](/assets/plotio.png)


Uma dica de ouro é observar o código de outras apresentações para se ter ideia do que fazer com o seu próprio material, ou você pode se perder procurando funcionalidades que nem sabe se existem. Por isso deixo aqui disponível [o código fonte](https://github.com/edumangabeira/R_exercicios/blob/master/georgeFloyd.Rmd) de uma [apresentação](https://rpubs.com/Edumangabeira/634176).

Espero que tenha gostado e até a próxima!

