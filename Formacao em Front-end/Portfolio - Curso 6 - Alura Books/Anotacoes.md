# Links úteis

## Cores

https://coolors.co/
https://color.adobe.com/pt/create/color-wheel
https://colorhunt.co/

## Documentação

https://www.w3schools.com/

## Responsividade

Usamos rem para tamanhos adaptativos de fonte a escala é de 1rem = 16px;
Outros recursos utilizam porcentagem como unidade de medida adaptativa

# Curso 6

## Aula 4 - BEM
-> luri, existe alguma link para artigo da alura que voce possa me indicar para entender porque em dado momento a professora usa um ou dois hifens para definir uma classe? exemplo: 'container__titulo--negrito' e 'container__imagem-transparente'

-> Claro, vou tentar te ajudar com essa dúvida!

Essa convenção de usar um ou dois hifens para definir classes CSS é conhecida como "BEM" (Block, Element, Modifier), que é uma metodologia de nomenclatura de classes muito utilizada em projetos de desenvolvimento web.

O BEM ajuda a criar um código CSS mais organizado e escalável, especialmente em projetos grandes. Aqui está uma breve explicação sobre essa convenção:

Um bloco (Block) representa um componente independente, como um cabeçalho, um menu ou um botão.
Um elemento (Element) é uma parte de um bloco, como um título, uma imagem ou um link dentro de um cabeçalho.
Um modificador (Modifier) é uma variação de um bloco ou elemento, como um botão primário ou secundário.
Então, no exemplo que você citou:

container__titulo--negrito seria um elemento (título) dentro de um bloco (container), com um modificador (negrito).
container__imagem-transparente seria um elemento (imagem) dentro de um bloco (container), com um modificador (transparente).
A Alura tem um ótimo artigo que explica melhor essa metodologia BEM e como aplicá-la em seus projetos CSS. Você pode encontrá-lo neste link:

Artigo da Alura sobre a metodologia BEM

Espero que essa explicação e o link do artigo ajudem a esclarecer sua dúvida! Se tiver mais alguma questão, fique à vontade para perguntar.

-> voce chegou quase luri, entre 'titulo' e 'negrito' existem 2 hifens, ao passo que, entre 'imagem' e 'transparente' existe apenas um . Vou conferir o artigo que voce me mostrou, mas teria como você resumir o porque ela difere o uso dos hifens entre o elemento e seu modificador?

-> Entendi, você está certo. A diferença no uso de um ou dois hifens entre o elemento e o modificador é importante.

Segundo a metodologia BEM, a convenção é:

Usar dois hifens -- para separar o elemento do modificador.
Usar um único hífen - para separar palavras dentro de um elemento ou modificador.
Então, no exemplo:

container__titulo--negrito

container__titulo é o elemento (título) dentro do bloco (container)
--negrito é o modificador desse elemento
container__imagem-transparente

container__imagem é o elemento (imagem) dentro do bloco (container)
-transparente é o modificador desse elemento
A diferença no uso de um ou dois hifens ajuda a deixar a estrutura da classe mais clara e fácil de entender. Os dois hifens -- separam de forma mais evidente o elemento do seu modificador.

Essa convenção de nomenclatura faz parte das melhores práticas da metodologia BEM e ajuda a manter o CSS organizado, principalmente em projetos maiores. O artigo da Alura deve explicar melhor essa diferença.

Espero que essa explicação complementar tenha ajudado a esclarecer a sua dúvida. Qualquer outra pergunta, fique à vontade!