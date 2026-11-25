# Elias Sousa Campos

Backend em Java e Spring Boot, front-end em TypeScript.

Fortaleza, Ceará · Ciência da Computação na UNIFOR · [LinkedIn](https://www.linkedin.com/in/eliascamposdev/)

## Projetos

### [livro-da-guilda](https://github.com/EliasCamposDEV/livro-da-guilda) · [demo](https://livro-da-guilda.onrender.com/swagger-ui.html)

API REST de usuários em Java 21, Spring Boot 4.1.3 e MongoDB. JWT com refresh rotativo (reúso é recusado), papéis `ADMIN` e `USER`, erros em `application/problem+json` com `code` e rate limit no login. Troca de senha e logout revogam sessões. Swagger com Authorize, Docker Compose e CI rodando `mvn verify` com SpotBugs, JaCoCo e CodeQL. A demo é somente leitura.

### [extrato-falado](https://github.com/EliasCamposDEV/extrato-falado) · [demo](https://extrato-falado.onrender.com)

Chat sobre o extrato bancário. O modelo só traduz a pergunta para um `QuerySpec` validado, e quem soma é o SQLite; ele nunca vê um valor, então errar a conta é impossível por construção. O SQL aparece junto da resposta. No uso local, importa CSV, OFX e PDF (com OCR quando o PDF é imagem), detecta fatura de cartão e transferências internas. A demo pública permite consultas e lançamentos manuais. 111 testes.

## Outros repositórios

- **[grimorio-de-vendas](https://github.com/EliasCamposDEV/grimorio-de-vendas)**: toolkit em Python (pandas e openpyxl) que limpa CSV, calcula KPIs e gera relatório Excel com gráficos. 17 testes e `ruff` no CI.
- **[sistema-autenticacao](https://github.com/EliasCamposDEV/sistema-autenticacao)**: autenticação com JWT e refresh tokens em Node.js, Express e MongoDB. 26 testes.
- **[schoolControl](https://github.com/EliasCamposDEV/schoolControl)**: gestão acadêmica em Haskell (IHP e PostgreSQL), com o domínio escrito em paradigma funcional puro.
- **[8_Puzzle_Solver](https://github.com/EliasCamposDEV/8_Puzzle_Solver)**: 8-puzzle resolvido como problema SAT (PySAT e Glucose3), não por busca heurística.
- **[cpf_validator](https://github.com/EliasCamposDEV/cpf_validator)**: validação de CPF em Python, com cálculo e conferência dos dois dígitos verificadores.

## Stack

`Java` · `Spring Boot` · `Spring Security` · `MongoDB` · `JWT` · `Docker` · `TypeScript` · `React` · `Node.js` · `Python` · `SQLite` · `Haskell`

## O que procuro

Cursando Ciência da Computação na UNIFOR. Procuro estágio em desenvolvimento de software, engenharia de software ou IA aplicada, em Fortaleza ou remoto.

Quero entrar num time que já entrega software com esse nível de cuidado, aprender com quem fez isso muitas vezes e continuar construindo projeto de verdade: com teste, documentação, privacidade e deploy funcionando.

## Contato

[LinkedIn](https://www.linkedin.com/in/eliascamposdev/)
