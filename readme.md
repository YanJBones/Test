# REPOSITORIO MASTER

POR QUE FAZER UM README? (https://www.alura.com.br/artigos/escrever-bom-readme?_gl=1*xd9a5z*_ga*MjA2MTIyMzg1NC4xNjQ0MDYxMjYy*_ga_59FP0KYKSM*MTY4OTE4MTAzMi43NS4xLjE2ODkxODIxMjUuMC4wLjA.*_fplc*U2tNZUNlV3VQaTRDTlhoeFFpSFgzRWxZUWpuRDRxRnQxUzFjQXU0SkhOWTBKQzB1enlRckQzOCUyQnYlMkZVTnQxdzJpOWJ0blZMV2dWSERPWUNFYnhyakpCQW5JZCUyQlFFVGVWaHU1SGtNckJpZmZ1MFBzVkZ4MzAwWFJDVFBPclJnJTNEJTNE)

Documentar o projeto para quem for visitar seu repositório saiba do que se trata. Além disso, utilizam o perfil GitHub como portfólio, é interessante apostar em arquivos README para deixar os projetos mais atrativos até mesmo para recrutadores.
Conseguimos ver alguns pontos que podemos destacar no seu README, como:

1 - Título e Imagem de capa;
2 - Badges;
3 - Índice;
4 - Descrição do Projeto;
5 - Status do Projeto;
6 - Funcionalidades e Demonstração da Aplicação;
7 - Acesso ao Projeto;
8 - Tecnologias utilizadas;
9 - Pessoas Contribuidoras;
10 - Pessoas Desenvolvedoras do Projeto;
11 - Licença.

1 - TITULO E IMAGEM DE CAPA
Assim que você adicionar um README, ele já irá iniciar com o título sendo o nome do seu repositório. Mas você pode mudar ele e colocar um nome descritivo.

Ao escolher o título, você pode colocá-lo dessa maneira:
# Seu título aqui

Caso queira colocar ele centralizado, você pode utilizar tags do HTML que funcionam normalmente, dessa forma:
<h1 align="center"> Seu título aqui </h1>

Você pode fazer uma capa ou logo do projeto para colocar após o título. Particularmente, gosto bastante do Canva para fazer artes, com o plano gratuito já é possível encontrar algumas ferramentas legais. Eventualmente, caso a logo for uma arte do título ela pode substituir o título.

Mas como colocar a imagem no arquivo? Assim que você fizer ou encontrar sua arte, você pode abrir ela no explorador de arquivos e arrastá-la para o arquivo do README em edição. Dentro dos colchetes [], irá aparecer o nome do arquivo da imagem como descrição, mas é interessante que você descreva detalhadamente do que se trata para ajudar na acessibilidade. E dentro dos parênteses aparece um link da sua imagem que o GitHub gera ao converter e hospedar ela.
["descrição da imagem"] (http://user-imagens.githubuser.com/7819115165.asdguyagsduas.png)

Outra maneira de colocar imagem, que é mais segura, seria subindo a imagem para seu próprio repositório ou utilizando serviços de hospedagem de imagens como o imgur ou o pasteboard e colocar o link gerado em markdown, dessa forma:
![descrição da imagem](url da imagem gerado pelo serviço de hospedagem ou GitHub)



2 - BADGES
Alguns repositórios utilizam badges, que na tradução literal é distintivo, emblema ou insígnia. Seus objetivos são indicar o estado atual do projeto, licença caso tenha, versões, dependências, testes e entre outros. Caso queira fazer suas badges, você pode utilizar o Shields.io, ele fornece na página principal diversos exemplos de Badges e, além disso, nele você pode colar o link do seu repositório do GitHub na caixa de texto inicial, assim automaticamente ele irá sugerir algumas Badges para você utilizar no seu projeto, fornecendo o link da Badge para copiar e colar no seu README.
Exemplo:
1) Status do projeto:
Código gerado:
![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

ou centralizado
<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

2) Stars do projeto:
Codigo gerado:
![GitHub Org's stars](https://img.shields.io/github/stars/camilafernanda?style=social)



3 - INDICE
O GitHub gera automaticamente um índice para arquivos README, tendo como base os títulos da seção. Para visualizá-lo, selecione o ícone de menu no canto superior esquerdo do arquivo. Principalmente em READMEs extensos, essa é uma ferramenta excelente para navegar pelo documento, pois redireciona o usuário para o tópico selecionado.

Entretanto, caso você tenha interesse em fazer seu próprio índice para ser visualizado no arquivo, também é possível fazer em Markdown.

Exemplo:
# Índice 

* [Título e Imagem de capa](#Título-e-Imagem-de-capa)
* [Badges](#badges)
* [Índice](#índice)
* [Descrição do Projeto](#descrição-do-projeto)
* [Status do Projeto](#status-do-Projeto)
* [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
* [Acesso ao Projeto](#acesso-ao-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Pessoas Contribuidoras](#pessoas-contribuidoras)
* [Pessoas Desenvolvedoras do Projeto](#pessoas-desenvolvedoras)
* [Licença](#licença)
* [Conclusão](#conclusão)


4 - DESCRIÇÃO DO PROJETO
Como é um objetivo do arquivo README descrever o projeto, é legal que você apresente logo após o título ou imagem de capa e/ou Badges caso tenha, uma breve explicação do seu projeto com seu objetivo principal.



5 - STATUS DO PROJETO
Caso você opte por não utilizar Badges sobre o status do projeto, é interessante que você coloque essa informação no próprio texto mesmo. Exemplo:
> :construction: Projeto em construção :construction:

Ou centralizado:
<h4 align="center"> 
    :construction:  Projeto em construção  :construction:
</h4>

Nesse exemplo foi utilizado o emoji :construction:, mas pode utilizar em qualquer lugar do arquivo, como antes dos subtítulos. Nesse Gist (https://gist.github.com/rxaviers/7360908) pode encontrar uma variedade de emojis para utilizar no seu README e deixá-lo mais descontraído.



6 - FUNCIONALIDADES E DEMONSTRAÇÃO DA APLICAÇÃO
Você pode listar as funcionalidades do seu projeto para facilitar o entendimento do usuário. Para isso, você pode fazer dessa maneira:
# :hammer: Funcionalidades do projeto

- `Funcionalidade 1`: descrição da funcionalidade 1
- `Funcionalidade 2`: descrição da funcionalidade 2
- `Funcionalidade 2a`: descrição da funcionalidade 2a relacionada à funcionalidade 2
- `Funcionalidade 3`: descrição da funcionalidade 3

Além disso, se for possível, é interessante apresentar as funcionalidades com um exemplo visual do projeto, como gif, imagens ou vídeo.



7 - ACESSO AO PROJETO
Caso o seu projeto esteja no ar com algum serviço de hospedagem, você pode disponibilizar o link para o mesmo. Caso contrário, você pode apostar em gifs e imagens, como citado anteriormente, bem como indicar como o usuário pode baixar o projeto, abrir e executar. Como pode ser feito em Markdown:
# 📁 Acesso ao projeto

**Indique como é possível baixar ou acessar o código fonte do projeto, seja projeto inicial ou final**

# 🛠️ Abrir e rodar o projeto

**Apresente as instruções necessárias para abrir e executar o projeto**



8 - TECNOLOGIAS UTILIZADAS
Você também pode citar as tecnologias utilizadas no projeto, é uma ótima forma de demonstrar o que você anda estudando nesse mar que é a tecnologia.



9 - PESSOAS CONTRIBUIDORAS
Caso o seu projeto tenha contribuidores, é bacana adicionar eles no README



10 -  PESSOAS DESENVOLVEDORAS DO PROJETO
E agora entra você! É importante que você coloque sua foto também, caso não goste de fotos, vale o user padrão do GitHub ou fazer seu próprio Octocat. Além disso, você pode linkar seu usuário, para caso algum usuário queira entrar em contato ou reportar algo.
# Autores

| [<img src="https://avatars.githubusercontent.com/u/37356058?v=4" width=115><br><sub>Camila Fernanda Alves</sub>](https://github.com/camilafernanda) |  [<img src="https://avatars.githubusercontent.com/u/30351153?v=4" width=115><br><sub>Guilherme Lima</sub>](https://github.com/guilhermeonrails) |  [<img src="https://avatars.githubusercontent.com/u/8989346?v=4" width=115><br><sub>Alex Felipe</sub>](https://github.com/alexfelipe) |
| :---: | :---: | :---: |



11 - LICENÇA
Geralmente, os repositórios públicos no GitHub são utilizados para compartilhar softwares de código aberto. Porém, para que um repositório seja realmente de código aberto, ele precisa obter uma licença para que outros tenham a liberdade de usar, alterar e distribuir o software. Portanto, caso seu repositório tenha uma licença, é essencial que você coloque ela no seu README.

