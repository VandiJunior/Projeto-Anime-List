# AnimeList – Catálogo Interativo

Projeto acadêmico da disciplina Tópicos Especiais em Projeto e Desenvolvimento Web (TEPDW).

## Autoria
- Nome do(a) aluno(a): Vandi Vieira dos Santos Junior
- Curso: Ciência da Computação

## Objetivo
Desenvolver uma aplicação web para cadastrar, organizar, pesquisar e acompanhar animes, aplicando conceitos de HTML, CSS e TypeScript.

## Funcionalidades
- Cadastro com título, categoria, ano e estado.
- Exibição dos animes em cards.
- Busca por título.
- Filtro por categoria.
- Alteração entre assistido e não assistido.
- Exclusão de itens.
- Resumo com total, assistidos e não assistidos.
- Validação de campos e do ano informado.

## Tecnologias
HTML5, CSS3 e TypeScript 5.

## Requisitos
Node.js e npm instalados.

## Instalação
No terminal, dentro da pasta do projeto:

```bash
npm install
```

## Compilação do TypeScript
```bash
npm run build
```

O comando compila `src/app.ts` e gera `dist/app.js`.

## Execução
Depois da compilação, abra o `index.html` em um servidor local. Uma opção é executar:

```bash
npm run start
```

Acesse `http://localhost:8080`.

## Observação
Os dados ficam em memória durante o uso da página. Ao atualizar ou fechar o navegador, os cadastros adicionados são perdidos. Persistência em banco de dados não faz parte dos requisitos.
