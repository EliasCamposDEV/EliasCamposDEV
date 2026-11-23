# Elias Sousa Campos

Backend em **Java + Spring Boot**, front-end em **TypeScript**.

📍 Fortaleza, Ceará · Ciência da Computação (UNIFOR) · [LinkedIn](https://www.linkedin.com/in/eliascamposdev/)

## O que estou construindo

### [livro-da-guilda](https://github.com/EliasCamposDEV/livro-da-guilda) · [demo](https://livro-da-guilda.onrender.com/swagger-ui.html)

API REST de usuários em Java 21, Spring Boot 3.5 e MongoDB. JWT com **refresh token rotativo** (reúso é recusado), RBAC (`ADMIN`/`USER`), erros em `application/problem+json` com `code`, rate limit no login, troca de senha e logout que revogam sessões, Swagger com Authorize, Docker Compose e CI rodando `mvn verify` com SpotBugs e **56 testes**. Demo pública somente leitura.

### [extrato-falado](https://github.com/EliasCamposDEV/extrato-falado) · [demo](https://extrato-falado.onrender.com)

Chat sobre o extrato bancário onde o modelo **só traduz** a pergunta para um `QuerySpec` validado e quem soma é o SQLite; o LLM nunca vê um valor, então errar a conta é impossível por construção. O SQL gerado aparece junto da resposta. No uso local importa CSV, OFX e PDF (com OCR quando o PDF é imagem), detecta fatura de cartão e transferências internas; a demo pública permite consultas e lançamentos manuais. **111 testes**.

## Outros repositórios

- **[grimorio-de-vendas](https://github.com/EliasCamposDEV/grimorio-de-vendas)**: toolkit em Python (pandas e openpyxl) que limpa CSV, calcula KPIs e gera relatório Excel com gráficos; 17 testes e `ruff` no CI.
- **[sistema-autenticacao](https://github.com/EliasCamposDEV/sistema-autenticacao)**: autenticação com JWT e refresh tokens em Node.js, Express e MongoDB.
- **[schoolControl](https://github.com/EliasCamposDEV/schoolControl)**: gestão acadêmica em Haskell (IHP + PostgreSQL), com o domínio escrito em paradigma funcional puro.
- **[8_Puzzle_Solver](https://github.com/EliasCamposDEV/8_Puzzle_Solver)**: 8-puzzle resolvido como problema SAT (PySAT/Glucose3) em vez de busca heurística.
- **[cpf_validator](https://github.com/EliasCamposDEV/cpf_validator)**: validação de CPF em Python.

## Stack

`Java` · `Spring Boot` · `Spring Security` · `MongoDB` · `JWT` · `Docker` · `TypeScript` · `React` · `Node.js` · `Python` · `SQLite` · `Haskell`

## Objetivo

Atualmente, curso Ciência da Computação na UNIFOR e busco oportunidades de **estágio em Desenvolvimento de Software, Engenharia de Software e IA Aplicada**, em Fortaleza ou remoto. Quero contribuir com o que já construí, aprender com times experientes e continuar criando soluções reais, com testes, documentação, privacidade e deploy funcionando.

## Contato

[LinkedIn](https://www.linkedin.com/in/eliascamposdev/).
