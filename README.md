<div align="center">
<img src="https://github.com/LucasHProenca/Power-BI-Analyst/assets/106993403/c05ab973-8cc0-4555-949c-7a6329eef069" alt="" />
</div>


---

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-páginas">Páginas</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-autor">Autor</a> • 
</p>

## 💻 Sobre o projeto 

 
📟 Sales Report - Este projeto foi desenvolvido com o propósito de se assemelhar a um relátorios de vendas real, com diversas demonstrações e detalhes para melhor expor todas as informações relevantes de uma empresa.
Este projeto possui inúmeras funcionalidades, as quais detalharemos mais adiante.

Projeto desenvolvido durante o **Bootcamp de Ciência de Dados com Python** da [DIO](https://www.dio.me/en).
Esse bootcamp é uma experiência online, um programa com mais de 80 horas de experiência prática nas principais tecnologias que norteiam o Python, também oferece desafios de código e projetos individuais.

---

## ⚙️ Funcionalidades

  - [x] Diversos demonstrativos gráficos;
  - [x] Segmentadores por data completa ou ano;
  - [x] Possibilidade de mudança de tipo de gráfico exibido;
  - [x] Possibilidade de voltar o relatório as informações iniciais;
  - [x] Troca de página;  

---

## 📄 Páginas

#### ATENÇÃO!

O Sales Report foi feito pensado em desktop-first, no entanto, em breve traremos sua versão mobile.

### Desktop 

#### Página 1 - Relatório de Vendas 

![VendasP1](https://github.com/LucasHProenca/Power-BI-Analyst/assets/106993403/b2d7f23b-3300-4795-9031-a3d12d076312)

A página inicial do relatório pode ser vista de duas formas diferentes: Na primeira, como podemos observar pela foto acima, os gráficos de Vendas X Segmento e Total de Vendas X País são respectivamente, um gráfico de barras e um mapa, no entanto os botões presentes próximos aos mesmos nos possibilitam a alteração para um gráfico no formato de Donut, no caso de Vendas X Segmento, e um Tree Map, no caso de Total de Vendas X País, como podemos observar na imagem abaixo:

![VendasP@](https://github.com/LucasHProenca/Power-BI-Analyst/assets/106993403/06152f5b-21b6-4c32-8ad1-0ace28e7ab41)


#### Página de Inscrição

![SignupF1](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/2247ee54-9a76-4362-8207-a382faed9a1b)

![SignupF2](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/f365916b-5982-4c60-a5e2-b58f626f7166)

A página de inscrição possibilita ao usuário criar uma nova conta, porém, atente-se ao fato de que não será possível criar uma conta com o mesmo "Apelido" e/ou "E-mail" de outra pessoa, e que sua senha precisa respeitar o padrão estabelecido pelo backend

#### Feed

![HomePageF1](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/542bae49-7b30-4432-88aa-570df18062a1)

![HomePageF2](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/e7260931-7917-4206-b8c0-1d1c06a3691e)

Com a conta criada você irá se deparar com a tela inicial da nossa aplicação, onde poderá interagir com nossos milhões de outros usuários, seja criando uma nova publicação de um pensamento genial que você teve, até comentando em publicações das outras pessoas, curtindo-as, ou apenas observando o movimento da sua rede social. Lembrando que todo e qualquer like, dislike ou comentário ficará salvo (lembrando que não é possível dar like ou dislike no seu conteúdo autoral) até que o servidor fique inativo.

Você pode ver o botão de usuário localizado no topo esquerdo da página, salve ele na memória pois falaremos mais em breve.

Oferecemos também ao usuário uma opção de edição de suas publicações ou deleção das mesmas. MAS CUIDADO, mexer no que é dos outros nem sempre é bem visto, pensando nisso, caso o usuário tente editar ou excluir a publicação de outra pessoa, uma mensagem de erro será retornada, como podemos observar nas imagens abaixo:

![EditPostError](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/763a77e3-fadc-493c-b159-56f78b1e7cdc)

![DeletePostError](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/8711493c-0820-4f61-b967-9693300c05f9)

A seguir vamos acessar a página de comentários clicando no botão de "chat" ao lado esquerdo da opção de editar.

#### Página de comentários

![CommentsPageF1](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/0e96cde0-95b0-4421-9127-bbf0dfdeacf7)

![CommentsPageF2](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/edeacc4c-c63b-4887-b714-44fe3014e6a8)

Dentro da página de comentários oferecemos as mesmas funcionalidades e restrições que contém em seu feed, lembre-se de respeitá-las ou terá as mesmas mensagens. 

![EditCommentError](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/49ed8401-a2db-4848-8308-875f12c27a87)

![DeleteCommentError](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/8dd92fcb-f572-4f33-8cc2-3b508f911c6d)

Agora voltaremos ao feed, para acessarmos a página de usuários.

#### Página de usuários

![image](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/d1937972-b3ca-491f-bbb3-a8c87d82d9be)

Aqui teremos acesso a todos os usuários participantes da plataforma, e damos a ele a opção de editar suas informações pessoais ao clicar no botão de edição presente em seu card. Devido ao grande número de inscrições, buscamos deixar sempre as mais recentes logo no topo, portanto, será super tranquilo editar suas informações caso necessite.

Planejamos introduzir em breve mudanças significativas para que o usuário possa visualizar apenas suas próprias informações.

#### Página de edição dos dados pessoais

![userDetails](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/5d861ec4-0b57-48e0-a5e4-3c06430f7de7)

Ao chegar aqui, você irá se deparar com essas duas opções, a primeira para fazer a edição de seus dados pessoais e outra para deletar sua própria conta caso não tenha encontrado o que procura em nossa plataforma (não será o seu caso, fique tranquilo)

Escolhendo a primeira opção um menu se abrirá e dará ao usuário a opção de editar todas as suas informações simultaneamente, ou apenas uma / duas delas, observe que agora a "Marli" se chama "Mazinha", no entanto seu e-mail se mantém o mesmo.

![EditUser](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/3999a88b-b9a0-42a3-8da5-22ec47725126)

Mantenha sempre o cuidado de não tentar editar as informações de outra pessoa, pois não será possível concluir essa ação, como podemos ver abaixo: 

![EditUserError](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/6b9378fe-22ec-4fb9-9cd0-fa0bf6a7aeac)

Se por alguma razão não atendemos suas expectativas, existe a opção de deletar sua conta, a qual não recomendamos de forma alguma! Ao clicar no botão de "Excluir conta" um popup se abrirá pergunta se o usuário realmente deseja fazer isso.

![DeleteUser](https://github.com/LucasHProenca/Labeddit-frontend/assets/106993403/b2cad1b4-f023-45a6-b253-e77f28b60f0a)


#### IMPORTANTE

Independente de qual seja o resultado final, agradecemos pelo tempo que passamos juntos, e esperamos nos ver novamente em breve.

---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

#### ([API](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Client-side_web_APIs/Introduction)  +  [React](https://react.dev/))

-   **[React Router](https://reactrouter.com/en/main)**
-   **[React Context](https://legacy.reactjs.org/docs/context.html)**
-   **[Styled-components](https://styled-components.com/)**
-   **[Axios](https://axios-http.com/ptbr/docs/intro)**
-   **[Estado Global](https://coderpad.io/blog/development/global-state-management-react/)**

---

## 🙏 Agradecimentos

Aqui eu encerro minha jornada na [Labenu](https://www.labenu.com.br/), meu primeiro passo dentro do segmento de tecnologia, o primeiro de muitos, e com isso gostaria de agradecer primeiramente a Deus, a minha familia, meus pais, meu irmão e minha namorada que sempre me deram apoio durante todo esse processo, alguns dias eram mais difíceis do que outros, mas acredito que seja nesse momento onde mais temos a possibilidade de melhorar e crescer. Contudo, isso só foi possível graças ao time de professores sempre presentes para tirar quaisquer dúvidas que surgissem no caminho, agradeço imensamente a eles [Br](https://www.linkedin.com/in/brunoamorimramos/), [Marcelo](https://www.linkedin.com/in/marcelo-maia-7584b821b/), [Clara](https://www.linkedin.com/in/clara-meirelles/) e [Yuzo](https://www.linkedin.com/in/yuzokamoto/) sem vocês nada disso seria possível.

Gostaria de agradecer também a [Bianca](https://www.linkedin.com/in/biancacipriano/) e a todo o time de empregas, por todo o suporte que me deram e continuam dando.

E por último mas não menos importante, um agradecimento especial a um amigo que conheci durante o bootcamp, mas que espero levar pra vida e que possamos trabalhar juntos em breve [Vinicius](https://www.linkedin.com/in/devviniciussilva/)

---

## 🦸 Autor

 <img style="border-radius: 50%;"  src="https://github.com/LucasHProenca/Labecommerce-back-end/assets/106993403/9abf8ee7-9527-42f8-9151-04ccd3db2d97" width="100px;" alt="" />
 <br />
 <sub><b>Lucas Henrique Proença</b></sub>
 <br />

[![Linkedin Badge](https://img.shields.io/badge/-Lucas-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lucas-proen%C3%A7a-512650106/)](https://www.linkedin.com/in/lucas-proen%C3%A7a-512650106/) 

---
