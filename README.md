<h1>Vinícius Gondaline Silva</h1>

<p><strong>Desenvolvedor back-end / full stack</strong> · São Paulo, Brasil</p>

<p>
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img alt="Cloudflare Workers" src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
</p>

Trabalho com APIs REST e aplicações serverless na Cloudflare (Workers, Queues, D1 e R2), com dados em PostgreSQL. No front-end, React, Next.js e Tailwind.

Atuo em um produto SaaS de landing pages com mais de 2 milhões de páginas publicadas. A maior parte do meu trabalho está em repositórios privados; o que dá para mostrar está abaixo.

No dia a dia uso Claude Code e ChatGPT, inclusive conectados ao banco e aos logs via MCP, para acelerar investigação e análise de código, sempre com revisão e testes antes de ir para produção.

## Projetos

### [EventRelay](https://github.com/Gondaline/event-relay)

API de entrega de webhooks em Node.js, Express e PostgreSQL. Cada tentativa de entrega fica registrada no banco. Quando a falha é temporária, a entrega vai para uma fila no Cloudflare Queues e um Worker agenda novas tentativas com backoff progressivo; falhas definitivas, como um `404`, não são reenviadas. Tem autenticação por token e proteção contra SSRF.

### [Planilha IA](https://github.com/Gondaline/chat-ia) · [demo](https://planilha-chat-ia.pages.dev)

Chat com IA para análise de planilhas, em Next.js e TypeScript sobre Cloudflare Pages Functions. A requisição dispara em paralelo para vários provedores de IA e a primeira resposta válida vence, o que corta latência e mantém a aplicação de pé quando um provedor degrada.

### [Biblioteca Online](https://github.com/Gondaline/biblioteca-online)

API REST de livros, autores e editoras com Node.js, Express e MongoDB. Organizada em rotas, controllers, models e middlewares, com busca por filtros, paginação, ordenação, validação de dados e tratamento de erros centralizado.

## Laboratórios de estudo

### [CloudLab](https://github.com/Gondaline/aws-ec2-apache-lab) · [prévia](https://gondaline.github.io/aws-ec2-apache-lab/)

Página estática publicada em uma instância AWS EC2 com Apache. HTTP liberado ao público e SSH restrito ao IP do administrador por Security Group, com o passo a passo e as evidências de cada etapa documentados no README.

## Contato

<a href="https://www.linkedin.com/in/vinicius-gondaline-silva"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=inspire&logoColor=white"></a>
<a href="mailto:vigondaline@gmail.com"><img alt="E-mail" src="https://img.shields.io/badge/E--mail-vigondaline%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
