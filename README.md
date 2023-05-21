# Nome do Projeto 
ou
<h1 align="center">Nome do Projeto</h1>
Nome do Projeto
Com a descrição:

## Descrição do Projeto
<p align="center">Escrever uma breve descrição</p>
Escrever uma breve descrição

<h1 align="center">
    <a href="https://pt-br.reactjs.org/">🔗 React</a>
</h1>
<p align="center">🚀 lib para construir interfaces do usuário com componentes reutilizáveis</p>
🔗 React
🚀 lib para construir interfaces do usuário com componentes reutilizáveis

✅ Badges
Status: Opcional

É uma questão de gosto pessoal e comunicação. As badges são úteis para indicar o status do projeto: você pode colocar a versão dele, link para licença, quantidade de issues, status da build, status dos testes.  Vale muito a pena colocar.

As badges podem ficar no topo antes do título ou abaixo da descrição.

Use o site shields.io para gerar suas badges.

https://blog.rocketseat.com.br/content/images/2020/07/como-escreve-um-bom-read-me-image-1.png
Você pode criar a sua própria badge:

Os ícones de várias logos de produtos e tecnologias você encontra aqui: simpleicons.org.

Podemos customizar partir da URL a abaixo:

https://img.shields.io/static/v1?label=<LABEL>&message=<MESSAGE>&color=<COLOR>&style=<STYLE>&logo=<LOGO>
Os parâmetros significam:

LABEL: texto do campo esquerdo
MESSAGE: texto do campo direto
COLOR: cor do campo direito, pode usar RGB.
STYLE: estilo do badge inteiro. Podemos ter: plastic, flat, for-the-badge, social ou flat-square. Teste cada uma delas.
LOGO: logo do campo esquerdo
Como exemplo, vou escolher os seguintes parâmetros:

LABEL: como Blog
MESSAGE: como Rocketseat
COLOR: 7159c1
STYLE: como for-the-badge
LOGO: como GHOST
Podemos colocar ele no README assim em HTML:

<img src="https://img.shields.io/static/v1?label=Blog&message=Rocketseat&color=7159c1&style=for-the-badge&logo=ghost"/>
ou ainda em Markdown:

![Badge](https://img.shields.io/badge/Blog-Rocketseat-%237159c1?style=for-the-badge&logo=ghost)
Pronto. Veja como ficou o badge personalizado:


Legal que no site shields.io tem o input search / project URL que você cola o link do projeto do seu Github e ele sugere alguns badges.

https://blog.rocketseat.com.br/content/images/2020/07/como-escreve-um-bom-read-me-shields.png
Tem esse repositório com algumas badges prontas: Naereen/badges

✅ Tabela de Conteúdos
Status: Obrigatório

É ótimo colocar os índices de conteúdos, que é tabela onde a pessoa clica e vai para o tópico específico.

Exemplo com markdown:

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre](#Sobre)
   * [Tabela de Conteudo](#tabela-de-conteudo)
   * [Instalação](#instalacao)
   * [Como usar](#como-usar)
      * [Pre Requisitos](#pre-requisitos)
      * [Local files](#local-files)
      * [Remote files](#remote-files)
      * [Multiple files](#multiple-files)
      * [Combo](#combo)
   * [Tests](#testes)
   * [Tecnologias](#tecnologias)
<!--te-->
https://github.com/ekalinin/github-markdown-toc#table-of-contents
Resultado:

Tabela de conteúdos
Sobre
Tabela de Conteudo
Instalação
Como usar
Pre Requisitos
Local files
Remote files
Multiple files
Combo
Tests
Tecnologias
Se o README tiver poucos tópicos pode fazer inline, com HTML:

<p align="center">
 <a href="#objetivo">Objetivo</a> •
 <a href="#roadmap">Roadmap</a> • 
 <a href="#tecnologias">Tecnologias</a> • 
 <a href="#contribuicao">Contribuição</a> • 
 <a href="#licenc-a">Licença</a> • 
 <a href="#autor">Autor</a>
</p>
https://github.com/animavita/animavita
Resultado:

Objetivo • Roadmap • Tecnologias • Contribuição • Licença • Autor

No README.md do Github você pode usar HTML o que ajuda muito. 👌

✅ Status do Projeto
Status: Obrigatório

Indica se o projeto está em desenvolvimento ou já foi concluído.

<h4 align="center"> 
	🚧  React Select 🚀 Em construção...  🚧
</h4>
Resultado:

🚧 React Select 🚀 Em construção... 🚧
✅ Features
Status: Opcional

Você pode listar as funcionalidades da aplicação.

É opcional, porém é muito importante colocar. Isso ajuda demais as pessoas entenderem o que já tem feito, se estiver em construção você vai checkando o que está pronto.

Exemplo:

### Features

- [x] Cadastro de usuário
- [x] Cadastro de cliente
- [ ] Cadastro de produtos

No Github ou gist fica com essa aparência abaixo. Resultado:

https://blog.rocketseat.com.br/content/images/2020/07/Screen-Shot-2020-07-10-at-14.03.41.png
✅ Demonstração da aplicação
Status: Opcional
