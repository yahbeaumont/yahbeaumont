<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.pt.svg">
  <img src="assets/hero-light.pt.svg" alt="Hay Beaumont, Arquiteto de Software e Engenheiro" width="100%">
</picture>

**[English](README.md)**

A maior parte dos produtos que desenvolvo e coloco em produção é privada. O que compartilho aqui é a engenharia por trás deles: como os sistemas são arquitetados, quais decisões técnicas foram determinantes, os trade-offs envolvidos e os desafios encontrados ao transformar ideias em produtos reais.

Os repositórios abaixo apresentam estudos de caso de projetos efetivamente desenvolvidos, com uma abordagem técnica voltada a engenheiros e profissionais de tecnologia, não a apresentações comerciais. Não são projetos open source e não disponibilizam código-fonte proprietário nem dados de clientes.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sec-01-dark.pt.svg">
  <img src="assets/sec-01-light.pt.svg" alt="Trabalhos selecionados" width="100%">
</picture>

<a href="https://github.com/yahbeaumont/zoka-platform"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/zoka-platform-dark.pt.svg">
  <img src="assets/zoka-platform-light.pt.svg" alt="zoka-platform, plataforma de estudos com IA para estudantes brasileiros: comunidades, tutor e planos pagos, em produção. Next.js, Firebase, Stripe, Cloud Run." width="100%">
</picture></a>

<a href="https://github.com/yahbeaumont/vai-de-qual"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/vai-de-qual-dark.pt.svg">
  <img src="assets/vai-de-qual-light.pt.svg" alt="vai-de-qual, rede social de futebol: grafo social, planos pagos, créditos e repasse a criadores. NestJS, PostgreSQL, Redis, Stripe." width="100%">
</picture></a>

<a href="https://github.com/yahbeaumont/orbital-website"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/orbital-website-dark.pt.svg">
  <img src="assets/orbital-website-light.pt.svg" alt="orbital-website, site bilíngue para um ecossistema de hardware de IA local, gerado por pipeline em Python. Python, HTML, CSS, JavaScript." width="100%">
</picture></a>

<a href="https://github.com/yahbeaumont/orbital-os-platform"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/orbital-os-platform-dark.pt.svg">
  <img src="assets/orbital-os-platform-light.pt.svg" alt="orbital-os-platform, plataforma de IA local independente de hardware: arquitetura, orquestração de modelos e inferência local. Arquitetura, ADRs, pesquisa." width="100%">
</picture></a>

<a href="https://github.com/yahbeaumont/jer-crm"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/jer-crm-dark.pt.svg">
  <img src="assets/jer-crm-light.pt.svg" alt="jer-crm, CRM de prospecção com controle de acesso imposto por row-level security no PostgreSQL. Next.js, PostgreSQL, row-level security." width="100%">
</picture></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sec-02-dark.pt.svg">
  <img src="assets/sec-02-light.pt.svg" alt="Como eu trabalho" width="100%">
</picture>

Começo pelas restrições, não pelo framework. Requisitos regulatórios, tamanho da equipe, prioridades do negócio e prazos de entrega influenciam muito mais a arquitetura de um sistema do que preferências pessoais por uma biblioteca ou tecnologia específica.

Estabeleço fronteiras claras para dinheiro e identidade. O navegador nunca deve ser considerado confiável para autorizar operações financeiras, acessar dados de outros usuários ou modificar permissões. Sempre que uma regra puder ser imposta diretamente pelo banco de dados, ela deve ser.

Documento as decisões e suas razões. Registrar por que um sistema foi concebido de determinada maneira custa muito menos do que reconstruir esse raciocínio no futuro, especialmente quando quem precisa fazer isso sou eu, dois anos depois.

Prefiro infraestrutura previsível e ciclos curtos de feedback. Menos componentes desnecessários, estado observável, processos claros e mecanismos de rollback que realmente funcionam. Confiabilidade é resultado de decisões de engenharia deliberadas, não de complexidade desnecessária.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sec-03-dark.pt.svg">
  <img src="assets/sec-03-light.pt.svg" alt="Stack de tecnologia" width="100%">
</picture>

```text
linguagens   typescript · python · node.js
frameworks   nestjs · next.js · react
dados        postgresql · redis · firebase · cloud run
pagamentos   stripe · pix
ia           integração de llm · modelos de peso aberto · inferência local em hardware real
```

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sec-04-dark.pt.svg">
  <img src="assets/sec-04-light.pt.svg" alt="Notas" width="100%">
</picture>

Os estudos de caso estão disponíveis em **inglês** e **português brasileiro**. Cada repositório especifica seu escopo, seus limites e quais informações e materiais foram intencionalmente excluídos da publicação.
