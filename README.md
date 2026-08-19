# Roadmapsh

Projeto pessoal de estudos sobre desenvolvimento e tecnologia.

A proposta é simples:

```text
Estudar
   ↓
Aprender
   ↓
Escrever um artigo sobre o que foi estudado
   ↓
Publicar no GitHub
   ↓
Disponibilizar no GitHub Pages
```

O [roadmap.sh](https://roadmap.sh/) será utilizado como referência para orientar parte dos estudos, principalmente nas áreas de Frontend e Backend.

O objetivo deste projeto não é reproduzir o roadmap.sh nem criar um curso ou livro. A ideia é registrar aquilo que foi efetivamente estudado e aprendido.

## Princípio do projeto

**O que for estudado determina a estrutura do projeto.**

Não existe uma lista fixa de assuntos que precise ser criada antecipadamente.

Conforme um novo assunto for estudado, uma nova página poderá ser criada.

Exemplo:

```text
Estudo de Internet
        ↓
tracks/frontend/internet/
└── index.html
```

Depois:

```text
Estudo de DNS
        ↓
tracks/frontend/internet/
├── index.html
└── dns/
    └── index.html
```

Outro assunto pode surgir em outro momento:

```text
Estudo de PostgreSQL
        ↓
tracks/backend/postgresql/
└── index.html
```

A estrutura cresce conforme o aprendizado.

## Estrutura

```text
roadmapsh/
│
├── index.html
│
├── shared/
│   ├── css/
│   ├── js/
│   └── assets/
│
├── tracks/
│   ├── frontend/
│   │   └── README.md
│   │
│   └── backend/
│       └── README.md
│
└── README.md
```

### `index.html`

Página inicial do projeto.

Funciona como ponto de entrada para os conteúdos publicados.

### `shared/`

Arquivos compartilhados entre as páginas do projeto.

```text
shared/
├── css/
├── js/
└── assets/
```

A pasta será expandida somente quando surgir uma necessidade real.

### `tracks/`

Contém as áreas de estudo.

Inicialmente:

```text
tracks/
├── frontend/
└── backend/
```

Cada `track` representa uma área de estudo, e seu conteúdo será criado conforme os assuntos forem estudados.

Por exemplo:

```text
tracks/
└── frontend/
    ├── README.md
    ├── internet/
    ├── html/
    ├── css/
    └── javascript/
```

A estrutura interna não será criada antecipadamente. Ela será construída conforme os estudos avançarem.

Novas áreas poderão ser adicionadas no futuro quando fizerem sentido para o projeto.

## Produção do conteúdo

Os artigos serão produzidos a partir dos próprios estudos.

O processo esperado é:

```text
Pesquisar
   ↓
Estudar
   ↓
Testar e experimentar
   ↓
Compreender
   ↓
Escrever
   ↓
Revisar
   ↓
Publicar
```

A IA poderá ser utilizada como ferramenta de revisão, principalmente para verificar:

* erros conceituais;
* problemas técnicos;
* contradições;
* clareza da explicação;
* organização;
* erros de escrita.

O objetivo é que o conhecimento registrado seja resultado do estudo realizado durante a construção do projeto.

## Tecnologias

Neste estágio inicial, o projeto utiliza somente:

* HTML
* CSS
* JavaScript

Não há backend, banco de dados ou framework.

A proposta inicial é manter o projeto totalmente estático e utilizar o **GitHub Pages** para publicação.

## Publicação

O ciclo de publicação é simples:

```text
Estudo
   ↓
Criação do artigo
   ↓
Commit
   ↓
Push
   ↓
GitHub Pages
```

## Roadmap.sh

O [roadmap.sh](https://roadmap.sh/) será utilizado como referência para orientar os estudos.

Ele não define obrigatoriamente a estrutura deste projeto.

A organização dos conteúdos será determinada pelo próprio processo de aprendizado.

## Objetivo

Registrar publicamente a evolução dos estudos.

Cada artigo representa algo que foi estudado, compreendido e documentado.

O projeto será construído gradualmente, sem uma estrutura final previamente definida.

A estrutura cresce junto com o conhecimento.
