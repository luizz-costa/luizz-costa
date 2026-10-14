# Olá, eu sou o Luiz 👋

**Estudante de Sistemas de Informação na PUC Minas · Back-end e infraestrutura · Belo Horizonte, MG**

Busco um **estágio em back-end ou infraestrutura** para aprender com um time experiente e contribuir em sistemas reais.

[![Portfólio](https://img.shields.io/badge/Portf%C3%B3lio-luizz--costa.github.io-FFB300?style=for-the-badge)](https://luizz-costa.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luizz-costa/)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@luizzfcosta)

## Sobre mim

- Curso Sistemas de Informação na PUC Minas, com conclusão prevista para 12/2028.
- Desenvolvo APIs e sistemas web com **C# e .NET** e com **PHP**, usando **PostgreSQL** e **MySQL**.
- Gosto de cuidar do ambiente onde os sistemas rodam: mantenho um **servidor Debian** em casa, que acesso por SSH, com firewall configurado e meus projetos em **Docker**.
- Meu portfólio é um site estático publicado por **GitHub Actions** a cada push.
- Tenho interesse em **DevOps, cloud e segurança**, e estudo AWS, Terraform e redes.
- Uso IA generativa como apoio para estudar e desenvolver, sempre conferindo o resultado com testes e documentação.

## Projeto em destaque: Rodizio, gestão de escalas de serviço

API REST que substitui planilhas na montagem das escalas de serviço de uma equipe de segurança patrimonial, com **lista de prioridade automática**. Desenvolvi o sistema sozinho, numa equipe de 6, num **projeto de extensão da PUC Minas com uma empresa parceira**, dos requisitos aos testes. O repositório público é uma versão de portfólio, com organização e dados fictícios.

![Arquitetura do Rodizio](https://github.com/luizz-costa/rodizio-escalas/raw/main/img/arquitetura.svg)

- **API REST** em C# com .NET 8 e ASP.NET Core, documentada com Swagger.
- **Banco PostgreSQL** modelado com Entity Framework Core (code-first), com migrations aplicadas ao iniciar, chaves estrangeiras e índices únicos.
- **Regras de negócio:** quem está há mais tempo sem serviço vem primeiro, com contagem separada para dias úteis e para fins de semana e feriados; descanso mínimo entre serviços; impedimentos; dias permitidos por pessoa; e trocas que preservam o histórico.
- **Interface web** com 5 telas em HTML, CSS e JavaScript puro, servidas pela própria API, com proteção contra XSS.
- **Infraestrutura:** tudo sobe com um comando (Docker Compose), Dockerfile multi-stage, API rodando com usuário sem privilégios, portas presas em `127.0.0.1` e credenciais fora do repositório.
- **Testes:** gerador de dados de demonstração que preenche a escala desde uma data inicial até o dia atual, e roteiro com 34 casos de teste. O defeito encontrado foi corrigido e retestado.
- **Documentação:** requisitos levantados em entrevista com o usuário e 74 decisões técnicas registradas, com data e motivo.

**[Ver o código](https://github.com/luizz-costa/rodizio-escalas)** · **[Ver no portfólio](https://luizz-costa.github.io/projetos/sistema-de-escalas/)**

## Outros projetos

### Portfólio dinâmico com painel CMS · projeto pessoal

Meu portfólio anterior, em PHP 8 e MySQL, com painel administrativo para cadastrar, editar e excluir todo o conteúdo do site sem mexer no código. Login com senha em hash, consultas parametrizadas e escape contra XSS. Um ano depois, revisei o próprio código, encontrei duas falhas de segurança e corrigi.

**[Ver o código](https://github.com/luizz-costa/meu-blog-portfolio)** · **[Ver no portfólio](https://luizz-costa.github.io/projetos/cms-php/)**

### Este portfólio · Hugo + GitHub Actions + GitHub Pages

Site estático gerado com Hugo e publicado no GitHub Pages por um workflow do GitHub Actions, com as versões das ferramentas fixadas para o build ser igual no meu computador e no GitHub.

**[Ver o código](https://github.com/luizz-costa/luizz-costa.github.io)** · **[Ver o site](https://luizz-costa.github.io/)**

### ControleCerto · projeto acadêmico em equipe

Sistema web de gestão financeira, com dashboard, receitas, despesas e relatórios. Trabalhei nos requisitos, na documentação, na avaliação heurística, nos testes de usabilidade e nas telas de login e cadastro, com validação de formulário em HTML, CSS, JavaScript e Bootstrap.

**[Ver o código das telas de login e cadastro](https://github.com/luizz-costa/validacao-login-cadastro-frontend)**

## Tecnologias

**Uso em projetos**

<img src="https://skillicons.dev/icons?i=cs,dotnet,php,postgres,mysql,docker,linux,bash,git,github,githubactions,html,css,js,bootstrap&perline=15" alt="C#, .NET, PHP, PostgreSQL, MySQL, Docker, Linux, Shell Script, Git, GitHub, GitHub Actions, HTML, CSS, JavaScript e Bootstrap" />

C# · .NET 8 · ASP.NET Core Web API · Entity Framework Core · LINQ · Swagger · PHP · SQL · PostgreSQL · MySQL · Docker · Docker Compose · Linux · SSH · Shell Script · Git · GitHub · GitHub Actions · HTML · CSS · JavaScript · Bootstrap

**Estudando**

<img src="https://skillicons.dev/icons?i=aws,terraform,py,laravel" alt="AWS, Terraform, Python e Laravel" />

AWS · Terraform · Python · Laravel · Redes para DevOps · NoSQL (DynamoDB)

## Conceitos que aplico

| Área | Na prática |
|---|---|
| Back-end | APIs REST, POO, MVC, injeção de dependência, validação e respostas de erro padronizadas |
| Banco de dados | Modelagem relacional, normalização, migrations, chaves estrangeiras, índices e consultas SQL |
| Infraestrutura | Docker Compose, Linux por SSH, firewall, portas restritas, deploy automatizado com GitHub Actions |
| Qualidade | Casos de teste, dados de teste fictícios, commits pequenos com Conventional Commits e registro de decisões |
| Segurança | Senhas com hash, consultas parametrizadas, proteção contra XSS, credenciais fora do código e revisão do próprio código |
| Produto | Levantamento de requisitos com o usuário, avaliação heurística e testes de usabilidade |

## No momento

- Escrevendo os testes automatizados do Rodizio com xUnit
- Aprofundando Docker, Linux e AWS
- Evoluindo no inglês, hoje no nível intermediário (B1)

## Formação e cursos

**Bacharelado em Sistemas de Informação** · PUC Minas · 2025 a 2028

<details>
<summary>Cursos complementares</summary>

- Docker: do básico ao avançado · Udemy
- Formação Linux Completa · Udemy
- AWS Academy Cloud Foundations
- Terraform: Fundamentos de Infraestrutura como Código · Udemy
- Fundamentos de Redes para DevOps · Udemy
- Python para automação de tarefas · Udemy
- PHP Programando com Orientação a Objetos e Design Patterns · Pablo Dall'Oglio
- [Digital Safety and Security Awareness](https://www.credly.com/badges/dd6353bb-098f-42db-b6ef-9cfda9ee07cd/public_url) · Cisco

</details>

---

Quer conversar sobre uma vaga ou um projeto? Me chame no [LinkedIn](https://www.linkedin.com/in/luizz-costa/) ou veja mais no [portfólio](https://luizz-costa.github.io/).
